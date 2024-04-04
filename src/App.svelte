<script lang="ts">
   import "./app.css"
   import LinkButton from "./lib/LinkButton.svelte";
   import HeroImage from "./lib/HeroImage.svelte";
   import PhilSelfie from "./assets/PhilSelfie.png";
   import CV from "./assets/phillippe_morris-parent_CV.pdf"
   import gallar from "./assets/portfolio/Case study - Gallar mobile app.pdf"
   import hunchly from "./assets/portfolio/Case study - Hunchly 2 report builder.pdf"
   import fishfed from "./assets/portfolio/Showcase - FishFed.pdf"
   import lynnmore from "./assets/portfolio/Showcase - Lynnmore.pdf"
</script>

<main class="bg-gradient-to-b from-white to-zinc-100 max-h-full min-h-screen flex justify-center">
  <div id="maincontainer" class="flex flex-col items-center pt-8 pb-4 px-4 max-w-max">
    <HeroImage src={PhilSelfie} alt="A picture of Phil, a smiling adult with glasses, a nose ring, and a moustache wearing a denim jacket and black felt cap standing on a rocky shore"/>
    <div id="titletext" class="flex flex-col items-center gap-y-2 text-center py-4">
      <h1 class="text-3xl text-slate-800 font-medium text-center mb-1">Phil Morris-Parent <span class="text-sm block text-slate-600">(they/them)</span></h1>
      <h2 class="text-base text-slate-800 font-light">Product Management | UX Design | Leadership</h2>
      <div class="text-sm px-3 py-1 my-1 rounded-2xl bg-yellow-200 text-slate-800 max-w-fit font-medium">Available to work!</div>
    </div>
    <div class="flex flex-col gap-y-3 items-stretch self-stretch my-4">
      <LinkButton href="https://www.linkedin.com/in/phillippe-morris-parent-92997369/"> LinkedIn </LinkButton>
      <LinkButton href="https://github.com/phillmp"> GitHub </LinkButton>
    </div>
    <div class="w-2/3 border text-slate-600 my-2"/>
    <div class="flex flex-col gap-y-3 items-stretch self-stretch my-4">
      <LinkButton href={hunchly}> Hunchly 2 case study (PDF)</LinkButton>
      <LinkButton href={gallar}> Gallar mobile app case study (PDF)</LinkButton>
      <LinkButton href={lynnmore}> Lynnmore website showcase (PDF)</LinkButton>
      <LinkButton href={fishfed}> FishFed website showcase (PDF)</LinkButton>
    </div>

  </div>
</main>
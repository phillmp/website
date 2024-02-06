<script lang="ts">
   import "./app.css"
   import LinkButton from "./lib/LinkButton.svelte";
   import HeroImage from "./lib/HeroImage.svelte";
   import PhilSelfie from "./assets/PhilSelfie.png";
   import CV from "./assets/phillippe_morris-parent_CV.pdf"
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
      <LinkButton href={CV}> CV </LinkButton>
      <LinkButton href="https://www.linkedin.com/in/phillippe-morris-parent-92997369/"> LinkedIn </LinkButton>
      <LinkButton href="https://github.com/phillmp"> GitHub </LinkButton>
    </div>

  </div>
</main>
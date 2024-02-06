<script lang="ts">
   import "./app.css"
   import LinkButton from "./lib/LinkButton.svelte";
   import HeroImage from "./lib/HeroImage.svelte";
   import PhilSelfie from "./assets/PhilSelfie.png"
</script>

<main class="flex w-full h-full my-8 place-content-center">
  <div id="maincontainer" class="flex flex-col gap-y-4">
    <HeroImage src={PhilSelfie} alt="A picture of Phil, an adult with glasses, a nosering and a moustache wearing a denim jacket and black felt cap standing on a rocky shore"/>
    <h1>Phil Morris-Parent <span>(they/them)</span></h1>
    <h2>Product Management | UX Design | Leadership</h2>
    <h3>Available to work!</h3>
    <LinkButton href="#"> foo bar </LinkButton>
    <LinkButton href="#"> foo bar </LinkButton>
    <LinkButton href="#"> foo bar </LinkButton>
  </div>
</main>
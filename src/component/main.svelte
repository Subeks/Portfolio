<script>
  import Feature from "./feature.svelte";
  import HeroSection from "./heroSection.svelte";
  import Navbar from "./navbar.svelte";
  import Projects from "./projects.svelte";
</script>

<main>
  <div
    class=" bg-[url('/images/background-texture.jpg')] bg-fixed bg-contain flex flex-col gap-16 cursor-grab"
  >
    <div class="flex flex-col gap-4">
      <Navbar />
      <HeroSection />
    </div>

    <div class="bg-black bg-opacity-5 h-[0.1rem] mx-16"></div>

    <Feature />

    <div class="bg-black bg-opacity-5 h-[0.1rem] mx-16"></div>

    <Projects />
  </div>
</main>

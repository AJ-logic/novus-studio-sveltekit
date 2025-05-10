<script>
  import Header from "$lib/components/layout/Header.svelte";
  import Footer from "$lib/components/layout/Footer.svelte";
  import HeroSection from "$lib/components/sections/HeroSection.svelte";
  import ReasonsSections from "$lib/components/sections/ReasonsSections.svelte";
  import CTASection from "$lib/components/sections/CTASection.svelte";
</script>

<Header />
<main>
  <HeroSection />
  <ReasonsSections />
  <CTASection />
</main>
<Footer />

<script>
  import Header from "$lib/components/layout/Header.svelte";
  import HeroSection from "$lib/components/HeroSection.svelte";
  import ReasonsSections from "$lib/components/ReasonsSections.svelte";
  import CTASection from "$lib/components/CTASection.svelte";
  import Footer from "$lib/components/layout/Footer.svelte";
</script>

<Header />
<div class="page-container">
  <main>
    <HeroSection />
    <ReasonsSections />
    <CTASection />
  </main>
  <Footer />
</div>

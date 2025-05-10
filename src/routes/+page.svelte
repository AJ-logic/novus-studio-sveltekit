<script>
  export let data;
  import {
    HeroSection,
    ReasonsSection,
    CTASection,
  } from "$lib/components/sections";
</script>

<main>
  <HeroSection />
  <ReasonsSection reasons={data.reasons} />
  <CTASection />
</main>

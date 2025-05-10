<script>
  import CTAImage from "./cta-image.svelte";
  import CTAHeadlineOffer from "./cta-headline-offer.svelte";
  import CTADesc from "./cta-desc.svelte";
  import CTAButton from "./cta-button.svelte";
  import CTATimer from "./cta-timer.svelte";
  import CTAMeta from "./cta-meta.svelte";
</script>

<section class="cta-section">
  <!-- Mobile Layout -->
  <div class="mobile">
    <div class="cta">
      <CTAHeadlineOffer />
      <CTADesc />
      <CTAImage />
      <CTAButton />
      <CTATimer />
      <CTAMeta />
    </div>
  </div>

  <!-- Desktop Layout -->
  <div class="desktop">
    <div class="cta">
      <CTAImage />
      <div class="cta-content">
        <CTAHeadlineOffer />
        <CTADesc />
        <CTAButton />
        <CTATimer />
        <CTAMeta />
      </div>
    </div>
  </div>
</section>

<style>
  .cta-section {
    width: 100%;
    display: flex;
    justify-content: center;
    color: var(--color-blue, #00227d);
    padding: 48px 32px;
    text-align: center;
  }
  .cta {
    display: flex;
    flex-direction: column;
    align-items: center;
    width: 350px;
    padding: 43px 25px 33px 24px;
    border-radius: 18px;
    box-shadow: 0px 0px 20px 0px #00000040;
  }
  @media (min-width: 900px) {
    .cta-section {
      padding: 60px 0;
    }
    .cta {
      flex-direction: row;
      gap: 34px;
      width: 920px;
      max-width: 920px;
      padding: 60px 38px 35px 64px;
      border-radius: 10px;
    }
    .cta-content {
      width: 417px;
      text-align: center;
    }
  }
</style>

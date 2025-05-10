<script>
  export let reasons;
  import ReasonSection from "$lib/components/sections/reasons-section/reason-section.svelte";
</script>

<section
  id="reasons-section"
  class="reasons-section"
  aria-label="Reasons for Tariff-Free Sheets"
>
  {#each reasons as reason, i (i)}
    <ReasonSection {reason} index={i} />
  {/each}
</section>

<style>
  .reasons-section {
    width: 100%;
    display: flex;
    flex-direction: column;
    gap: 0;
  }
</style>

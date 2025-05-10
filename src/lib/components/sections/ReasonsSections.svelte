<script>
  import ReasonSection from "$lib/components/sections/ReasonSection.svelte";
  import { reasons } from "$lib/data/reasons";
</script>

<section class="reasons-section">
  {#each reasons as reason, i}
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

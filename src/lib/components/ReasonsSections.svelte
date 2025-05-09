<script>
  import ReasonSection from "$lib/components/ReasonSection.svelte";
  import { reasons } from "$lib/static/reasons";
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

  @media (min-width: 768px) {
    .reason-block {
      flex-direction: row;
      align-items: center;
    }
    .reason-block.reverse {
      flex-direction: row-reverse;
    }
    .reason-image,
    .reason-content {
      width: 50%;
    }
    .reason-content {
      padding: 4rem;
    }
  }
</style>

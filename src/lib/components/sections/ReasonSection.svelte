<script>
  export let index;
  export let reason;
  export let reverse = !(index % 2);
</script>

<div
  class="reason-block {reverse ? 'reverse' : ''}"
  style="
      --gap: {reason.style?.mobile?.gap};
      --padding: {reason.style?.mobile?.padding};
      --padding-right-h2: {reason.style?.mobile?.h2PRight};
      --font-size-h2: {reason.style?.mobile?.h2};
      --font-size-p: {reason.style?.mobile?.p};
      --font-weight-p: {reason.style?.mobile?.pWeight};
      --image-height: {reason.style?.mobile?.imgHeight};
      --padding-desktop: {reason.style?.desktop?.padding};
      --gap-desktop: {reason.style?.desktop?.gap};
      --padding-right-h2-desktop: {reason.style?.desktop?.h2PRight};
      --padding-right-p-desktop: {reason.style?.desktop?.pPRight};
    "
>
  <div class="reason-image">
    {#if index === 5}
      <img
        src={reason.imageMobile}
        alt={reason.alt}
        loading={"lazy"}
        decoding="async"
        class="mobile"
      />
      <img
        src={reason.imageDesktop}
        alt={reason.alt}
        loading={"lazy"}
        decoding="async"
        class="desktop"
      />
    {:else}
      <img
        src={reason.imageDesktop || reason.imageMobile}
        alt={reason.alt}
        loading={index === 0 ? "eager" : "lazy"}
        fetchpriority={index === 0 ? "high" : "auto"}
        decoding="async"
      />
    {/if}
  </div>
  <div class="reason-content">
    <h2>{index + 1}. {reason.title}</h2>
    <p class="mobile">{reason.textMobile}</p>
    <p class="desktop">{reason.textDesktop || reason.textMobile}</p>
  </div>
</div>

<style>
  .reason-block {
    display: flex;
    flex-direction: column;
    color: #fff;
    background: var(--color-blue, #00227d);
  }
  .reverse {
    color: #333b47;
    background: var(--color-light-blue, #e4f2fb);
  }
  .reason-image img {
    width: 100%;
    height: var(--image-height, 350px);
    object-fit: cover;
  }
  .reason-content {
    display: flex;
    flex-direction: column;
    gap: var(--gap, 14px);
    padding: var(--padding, 40px 20px);
  }
  h2 {
    color: #fff;
    font-size: var(--font-size-h2, 31px);
    font-weight: 550;
    line-height: 36px;
    letter-spacing: -0.46px;
    padding-right: var(--padding-right-h2, 0);
  }
  .reverse h2 {
    color: var(--color-blue, #00227d);
  }
  p {
    font-size: var(--font-size-p, 16px);
    font-weight: var(--font-weight-p, 390);
    line-height: 22px;
    letter-spacing: 0px;
  }
  @media (min-width: 900px) {
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
    .reason-image img {
      height: 609px;
    }
    .reason-content {
      gap: var(--gap-desktop, 14px);
      padding: var(--padding-desktop, 4rem);
    }
    h2 {
      padding-right: var(--padding-right-h2-desktop, 0);
      font-size: 38px;
      line-height: 46px;
      letter-spacing: -0.54px;
    }
    p {
      padding-right: var(--padding-right-p-desktop, 0);
      font-size: 18px;
      line-height: 26px;
      letter-spacing: 0;
    }
  }
</style>

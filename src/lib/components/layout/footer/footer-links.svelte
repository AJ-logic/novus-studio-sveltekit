<script>
  export let links = [
    { href: "/", label: "Privacy Policy" },
    { href: "/", label: "Care Guide" },
    { href: "/", label: "Terms of Use" },
  ];
</script>

<nav class="footer-links" aria-label="Footer">
  {#each links as { href, label }, i}
    <a {href}>{label}</a>
    {#if i < links.length - 1}
      <span class="footer-link-sep">|</span>
    {/if}
  {/each}
</nav>

<style>
  .footer-links {
    display: flex;
    gap: 16px;
    font-size: 12px;
    font-weight: 390;
    line-height: 22px;
    letter-spacing: 0;
  }
  .footer-links a {
    text-decoration: none;
  }
  .footer-link-sep {
    color: var(--color-blue, #00227d);
    opacity: 0.5;
  }
</style>

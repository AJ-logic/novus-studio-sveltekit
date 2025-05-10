<script>
  export let onDownArrowClick = () => {
    const el = document.getElementById("reasons-section");
    if (el) {
      el.scrollIntoView({ behavior: "smooth" });
    }
  };
</script>

<section class="hero">
  <div class="hero-image">
    <img
      src="/images/hero-woman.webp"
      alt="Woman sleeping peacefully"
      fetchpriority="high"
    />
  </div>
  <div class="hero-content">
    <h1>6 Reasons Tariff-Free Sheets Are the Answer to Your Night Sweats</h1>
    <p>
      NASA-inspired cooling, silver-infused freshness—without the luxury price
      hike.
    </p>
    <button
      class="down-arrow"
      tabindex="0"
      aria-label="Scroll to the next section"
      on:click={onDownArrowClick}
    ></button>
  </div>
</section>

<style>
  .hero {
    display: flex;
    flex-direction: column;
    width: 100%;
    background: #fff;
  }
  .hero-image img {
    width: 100%;
    height: 227px;
    object-fit: cover;
    object-position: 10%;
  }
  .hero-content {
    display: flex;
    flex-direction: column;
    align-items: center;
    text-align: center;
    gap: 8px;
    padding: 27px 35px 23.26px 34px;
    color: #fff;
    background: #001a72;
  }
  .hero-content h1 {
    font-weight: 450;
    font-size: 28px;
    line-height: 36px;
    letter-spacing: -0.4px;
  }
  .hero-content p {
    font-weight: 390;
    font-size: 17.6px;
    line-height: 22px;
    letter-spacing: 0px;
  }
  .down-arrow {
    display: inline-block;
    width: 16px;
    height: 16px;
    border-right: 4px solid #fff;
    border-bottom: 4px solid #fff;
    border-radius: 2px;
    transform: rotate(45deg);
    animation: bounce 1.5s infinite;
    cursor: pointer;
    outline: none;
  }
  @keyframes bounce {
    0%,
    100% {
      transform: rotate(45deg) translateY(0);
    }
    50% {
      transform: rotate(45deg) translateX(8px) translateY(8px);
    }
  }
  @media (min-width: 900px) {
    .hero-image img {
      height: 470px;
    }
    .hero-content {
      padding: 44px 326px 40px;
    }
    .hero-content h1 {
      font-size: 38px;
      line-height: 46px;
      letter-spacing: -0.54px;
      margin-bottom: 24px;
    }
    .hero-content p {
      font-size: 25px;
      line-height: 22px;
      letter-spacing: 0px;
      margin-bottom: 16px;
    }
  }
</style>

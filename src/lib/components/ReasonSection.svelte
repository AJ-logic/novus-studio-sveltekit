<script>
  export let index;
  export let reason;
  export let reverse = !(index % 2);
</script>

<div class="reason-block {reverse ? 'reverse' : ''}">
  <div class="reason-image">
    <img
      src={reason.image}
      alt={reason.alt}
      loading={index === 0 ? "eager" : "lazy"}
      fetchpriority={index === 0 ? "high" : "auto"}
      decoding="async"
      width="414"
      height="350"
    />
  </div>
  <div class="reason-content">
    <h2><span>{index + 1}.</span> {reason.title}</h2>
    <p>{reason.text}</p>
  </div>
</div>

<style>
  .reason-block {
    display: flex;
    flex-direction: column;
    color: #fff;
    background: var(--color-blue, #00227d);
  }
  .reason-block.reverse {
    color: #333b47;
    background: var(--color-light-blue, #e4f2fb);
  }
  .reason-image img {
    width: 100%;
    height: 350px;
    object-fit: cover;
  }
  .reason-content {
    display: flex;
    flex-direction: column;
  }
  .reason-content h2 {
    color: #fff;
  }
  .reverse h2 {
    color: var(--color-blue, #00227d);
  }
  .reason-block:nth-child(1) .reason-content {
    gap: 17px;
    padding: 40px 14px 34px 34px;
  }
  .reason-block:nth-child(3) .reason-content h2 {
    font-size: 32px;
    font-weight: 550;
    line-height: 36px;
    letter-spacing: -0.46px;
  }
  .reason-block:nth-child(1) .reason-content p,
  .reason-block:nth-child(2) .reason-content p,
  .reason-block:nth-child(3) .reason-content p,
  .reason-block:nth-child(4) .reason-content p,
  .reason-block:nth-child(5) .reason-content p,
  .reason-block:nth-child(6) .reason-content p {
    line-height: 22px;
    letter-spacing: 0px;
  }
  .reason-block:nth-child(1) .reason-content p {
    font-size: 16px;
    font-weight: 400;
  }
  .reason-block:nth-child(2) .reason-content {
    gap: 13px;
    padding: 40px 35px 54px 34px;
  }
  .reason-block:nth-child(1) .reason-content h2,
  .reason-block:nth-child(2) .reason-content h2,
  .reason-block:nth-child(4) .reason-content h2,
  .reason-block:nth-child(5) .reason-content h2,
  .reason-block:nth-child(6) .reason-content h2 {
    font-size: 31px;
    font-weight: 550;
    line-height: 36px;
    letter-spacing: -0.46px;
  }
  .reason-block:nth-child(2) .reason-content p {
    font-size: 15.2px;
    font-weight: 390;
  }
  .reason-block:nth-child(3) .reason-content {
    gap: 17px;
    padding: 40px 35px 38px 34px;
  }
  .reason-block:nth-child(3) .reason-content p {
    font-size: 15.4px;
    font-weight: 390;
  }
  .reason-block:nth-child(4) .reason-content {
    gap: 17px;
    padding: 27px 38px 54px 34px;
  }
  .reason-block:nth-child(4) .reason-content p {
    font-size: 16px;
    font-weight: 300;
  }
  .reason-block:nth-child(5) .reason-content {
    gap: 14px;
    padding: 40px 35px 48px 34px;
  }
  .reason-block:nth-child(5) .reason-content h2 {
    padding-right: 38px;
  }
  .reason-block:nth-child(5) .reason-content p {
    font-size: 15.6px;
    font-weight: 400;
  }
  .reason-block:nth-child(6) .reason-image img {
    height: 341px;
  }
  .reason-block:nth-child(6) .reason-content {
    gap: 14px;
    padding: 40px 33px 64px 34px;
  }
  .reason-block:nth-child(6) .reason-content p {
    font-size: 15.6px;
    font-weight: 300;
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
    .reason-image img,
    .reason-block:nth-child(6) .reason-image img {
      height: 609px;
    }
    .reason-block:nth-child(1) .reason-content {
      gap: 14px;
      padding: 184px 112px 188px 112px;
    }
    .reason-block:nth-child(1) .reason-content h2,
    .reason-block:nth-child(2) .reason-content h2,
    .reason-block:nth-child(3) .reason-content h2,
    .reason-block:nth-child(4) .reason-content h2,
    .reason-block:nth-child(5) .reason-content h2,
    .reason-block:nth-child(6) .reason-content h2 {
      font-size: 38px;
      line-height: 46px;
      letter-spacing: -0.54px;
    }
    .reason-block:nth-child(1) .reason-content p,
    .reason-block:nth-child(2) .reason-content p,
    .reason-block:nth-child(3) .reason-content p,
    .reason-block:nth-child(4) .reason-content p,
    .reason-block:nth-child(5) .reason-content p,
    .reason-block:nth-child(6) .reason-content p {
      font-size: 18px;
      line-height: 26px;
      letter-spacing: 0px;
    }
    .reason-block:nth-child(2) .reason-content {
      gap: 14px;
      padding: 199px 105.06px 199px 104.94px;
    }
    .reason-block:nth-child(2) .reason-content h2 {
      padding-right: 29px;
    }
    .reason-block:nth-child(3) .reason-content {
      gap: 14px;
      padding: 199px 113.06px 199px 113px;
    }
    .reason-block:nth-child(3) .reason-content p,
    .reason-block:nth-child(4) .reason-content p {
      font-size: 17.8px;
    }
    .reason-block:nth-child(4) .reason-content {
      gap: 10px;
      padding: 201px 100px 202px 110px;
    }
    .reason-block:nth-child(5) .reason-content {
      gap: 14px;
      padding: 199px 121px 199px 120px;
    }
    .reason-block:nth-child(6) .reason-content {
      gap: 10px;
      padding: 212px 86px 216px 87px;
    }
    .reason-block:nth-child(6) .reason-content p {
      padding-right: 37px;
    }
  }
</style>

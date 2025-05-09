<footer class="footer">
  <div class="footer-top">
    <div class="footer-logo">
      <img src="/images/logo.png" alt="Logo" class="logo" />
    </div>
    <div class="footer-company">
      <div class="footer-company-title">MIRACLE BRAND LLC</div>
      <div class="footer-company-grid">
        <div class="footer-company-col">
          <p>111 Town Square Place</p>
          <p>Suite 1203 PMB 1065</p>
          <p>Jersey City, New Jersey 07310</p>
        </div>
        <div class="footer-company-col">
          <p>1501 Haines St.</p>
          <p>Jacksonville, FL 32206</p>
          <p>(888) 683-4875</p>
        </div>
      </div>
    </div>
    <div class="footer-info">
      <div class="footer-info-title">INFO</div>
      <p class="footer-info-bold">Shipping Information</p>
      <p>UPS ground 2-7 business days</p>
      <p class="footer-info-bold">Business Licensing Information</p>
      <p>EIN: 83-3059849</p>
    </div>
    <div class="footer-company-mail-wrap">
      <p class="footer-company-mail-title">CUSTOMER SUPPORT</p>
      <p class="footer-company-mail-box">
        <span class="footer-company-mail-icon">
          <img src="/images/icons/email.svg" alt="Email" />
        </span>
        <span class="footer-company-mail">hello@miraclebrand.co</span>
      </p>
    </div>
  </div>
  <div class="separator"></div>
  <div class="footer-disclaimer-box">
    <p>
      <b>Disclaimer:</b> this is an advertisement, using a fictional customer but
      discussing experiences that are common to real customers of Miracle brand.
    </p>
    <p>
      This is an advertisement and not an actual news article, blog, or consumer
      protection update.
    </p>
    <p>
      The story depicted on this site and the person depicted in the story are
      not actual news. Rather, this story is based on the results that some
      people who have used these products have achieved. The results portrayed
      in the story and in the comments are illustrative, and may not be the
      results that you achieve with these products. This page could receive
      compensation for clicks on or purchase of products featured on this site.
    </p>
  </div>
  <div class="footer-bottom">
    <div class="footer-links">
      <a href="#">Privacy Policy</a>
      <span class="footer-link-sep">|</span>
      <a href="#">Care Guide</a>
      <span class="footer-link-sep">|</span>
      <a href="#">Terms of Use</a>
    </div>
    <div class="footer-copyright">
      Copyright 2022. Miracle Brand LLC. All rights reserved.
    </div>
  </div>
</footer>

<style>
  .footer {
    color: var(--color-blue, #00227d);
    background: var(--color-light-blue, #e4f2fb);
    padding: 50px 23.5px 59.45px 25px;
  }
  .footer-logo {
    margin-bottom: 54px;
  }
  .footer-company-title {
    font-size: 12px;
    font-weight: 550;
    line-height: 100%;
    letter-spacing: 2px;
    margin-bottom: 10px;
  }
  .footer-company-grid {
    display: flex;
    justify-content: space-between;
    margin-bottom: 2.8rem;
  }
  .footer-company-col p,
  .footer-info p,
  .footer-company-mail-wrap p,
  .footer-disclaimer-box p {
    font-size: 14px;
    font-weight: 400;
    margin: 6px 0;
  }
  .footer-info {
    margin-bottom: 36px;
  }
  .footer-info-title {
    font-size: 12px;
    font-weight: 550;
    line-height: 100%;
    letter-spacing: 2px;
    margin-bottom: 10px;
  }
  p.footer-info-bold {
    font-weight: 700;
  }
  p.footer-company-mail-title {
    font-weight: 700;
    letter-spacing: 2px;
    font-size: 12px;
    margin-bottom: 8px;
  }
  .footer-company-mail-box {
    display: flex;
    align-items: center;
    gap: 12px;
  }
  .footer-company-mail {
    font-size: 22px;
    font-weight: 550;
    line-height: 26px;
    letter-spacing: 0px;
  }
  .separator {
    margin: 25.24px 0 20.76px 0;
    border-bottom: 1px groove #00207d20;
  }
  .footer-disclaimer-box {
    display: flex;
    flex-direction: column;
    gap: 14px;
  }
  .footer-disclaimer-box p {
    font-size: 11.6px;
    font-weight: 390;
    line-height: 14px;
    letter-spacing: 0;
    margin: 0;
  }
  .footer-bottom {
    display: flex;
    flex-direction: column;
    gap: 24px;
    margin-top: 54px;
  }
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
  .footer-copyright {
    font-size: 12px;
    font-weight: 390;
    line-height: 100%;
    letter-spacing: 0;
  }
  @media (min-width: 600px) {
    .footer-company-grid {
      flex-direction: row;
      gap: 2.5rem;
    }
    .footer-info-grid {
      flex-direction: row;
      gap: 2.5rem;
    }
    .footer-company-col,
    .footer-info-col {
      min-width: 200px;
    }
  }
</style>

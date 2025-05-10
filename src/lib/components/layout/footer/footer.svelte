<script>
  import FooterLogo from "./footer-logo.svelte";
  import FooterCompanyInfo from "./footer-company-info.svelte";
  import FooterInfo from "./footer-info.svelte";
  import FooterSupport from "./footer-support.svelte";
  import FooterDisclaimer from "./footer-disclaimer.svelte";
  import FooterLinks from "./footer-links.svelte";
</script>

<footer class="footer">
  <div class="footer-wrap">
    <div class="footer-top">
      <FooterLogo />
      <div class="footer-info-wrap">
        <FooterCompanyInfo />
        <FooterInfo />
        <FooterSupport />
      </div>
    </div>
    <div class="separator"></div>
    <FooterDisclaimer />
    <div class="footer-bottom">
      <FooterLinks />
      <div class="footer-copyright">
        Copyright 2022. Miracle Brand LLC. All rights reserved.
      </div>
    </div>
  </div>
</footer>

<style>
  .footer {
    color: var(--color-blue, #00227d);
    background: var(--color-light-blue, #e4f2fb);
  }
  .footer-wrap {
    padding: 50px 23.5px 59.45px 25px;
  }
  .footer-info-wrap {
    display: flex;
    flex-direction: column;
  }
  .separator {
    margin: 25.24px 0 20.76px 0;
    border-bottom: 1px groove #00207d20;
  }
  .footer-bottom {
    display: flex;
    flex-direction: column;
    gap: 24px;
    margin-top: 54px;
  }
  .footer-copyright {
    font-size: 12px;
    font-weight: 390;
    line-height: 100%;
    letter-spacing: 0;
  }
  @media (min-width: 900px) {
    .footer-wrap {
      max-width: 1440px;
      margin: 0 auto;
      padding: 61px 164px 35px 165px;
    }
    .footer-top {
      flex-direction: row;
      justify-content: space-between;
    }
    .footer-info-wrap {
      flex-direction: row;
      justify-content: space-between;
    }
    .separator {
      margin: 30px 0 28px 0;
      opacity: 0;
    }
    .footer-bottom {
      flex-direction: row-reverse;
      align-items: center;
      justify-content: space-between;
      margin-top: 38.8px;
    }
  }
</style>

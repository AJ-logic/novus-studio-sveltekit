<section class="cta-section">
  <!-- Mobile Layout -->
  <div class="cta-mobile">
    <div class="cta-headline-offer">
      <span class="cta-headline">TARIFF-FREE<br />COMFORT SALE</span>
      <span class="cta-offer">GET 20% OFF NOW</span>
    </div>
    <div class="cta-desc">
      <b>Beat the price hikes</b> and sleep better<br />tonight. This
      <span class="limited"><b>limited time deal</b></span>
      is in high<br /> demand and stock keeps selling out.
    </div>
    <div class="cta-image-wrap">
      <img
        src="/images/cta-product.png"
        alt="Product bundle with towels"
        class="cta-img"
      />
    </div>
    <button class="cta-btn">
      <span class="checkmark">
        <img src="/images/icons/check.svg" alt="Check" />
      </span> GET YOUR MIRACLE NOW!
    </button>
    <div class="cta-timer-label">DEAL ENDING IN:</div>
    <div class="cta-timer">13:52</div>
    <div class="cta-meta-row">
      <span class="cta-meta-left">
        <span class="cta-icon">
          <img src="/images/icons/alert.svg" alt="Alert" />
        </span>
        <span class="cta-meta-desc">
          Sell-Out Risk:
          <span class="risk-high">High</span>
        </span>
      </span>
      <span class="separator"></span>
      <span class="cta-meta-right">
        <span class="cta-icon delivery">
          <img src="/images/icons/delivery.svg" alt="Delivery" />
        </span>
        <span class="cta-meta-desc">
          <span class="free-delivery">FREE</span>
          <span class="shipping">shipping</span>
        </span>
      </span>
    </div>
  </div>

  <!-- Desktop Layout -->
  <div class="cta-desktop">
    <div class="cta-image-wrap">
      <img
        class="cta-product"
        src="/images/cta-product.png"
        alt="Product bundle with towels"
      />
    </div>
    <div class="cta-content">
      <div class="cta-headline-offer">
        <span class="cta-headline">TARIFF-FREE COMFORT SALE</span>
        <span class="cta-offer">GET 20% OFF NOW</span>
      </div>
      <div class="cta-desc">
        <b>Beat the price hikes</b> and sleep better tonight. This
        <span class="limited"><b>limited time deal</b></span> is in high demand and
        stock keeps selling out.
      </div>
      <button class="cta-btn">
        <span class="checkmark">
          <img src="/images/icons/check.svg" alt="Check" />
        </span> GET YOUR MIRACLE NOW!
      </button>
      <div class="cta-timer-label">DEAL ENDING IN:</div>
      <div class="cta-timer">13:52</div>
      <div class="cta-meta-row">
        <span class="cta-meta-left">
          <span class="cta-icon">
            <img src="/images/icons/alert.svg" alt="Alert" />
          </span>
          <span class="cta-meta-desc">
            Sell-Out Risk:
            <span class="risk-high">High</span>
          </span>
        </span>
        <span class="separator"></span>
        <span class="cta-meta-right">
          <span class="cta-icon delivery">
            <img src="/images/icons/delivery.svg" alt="Delivery" />
          </span>
          <span class="cta-meta-desc">
            <span class="free-delivery">FREE</span>
            <span class="shipping"> shipping</span>
          </span>
        </span>
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
  .cta-mobile {
    display: flex;
    flex-direction: column;
    align-items: center;
    width: 100%;
    padding: 43px 25px 33px 24px;
    border-radius: 18px;
    box-shadow: 0px 0px 20px 0px #00000040;
  }
  .cta-desktop {
    display: none;
  }
  .cta-headline-offer {
    display: flex;
    width: 100%;
    flex-direction: column;
    align-items: center;
    gap: 4px;
    font-size: 30px;
    font-weight: 400;
    line-height: 31px;
    letter-spacing: -0.43px;
    margin-bottom: 12px;
  }
  .cta-offer {
    font-weight: 600;
  }
  .cta-desc {
    font-size: 16px;
    font-weight: 390;
    line-height: 20px;
    letter-spacing: 0px;
  }
  .cta-image-wrap {
    position: relative;
    display: flex;
    align-items: center;
    justify-content: center;
    width: 100%;
    height: 247.35px;
  }
  .cta-img {
    width: 350px;
    height: 255.35px;
  }
  .cta-btn {
    display: flex;
    align-items: center;
    justify-content: center;
    width: 100%;
    font-family: "Montserrat";
    font-size: 15px;
    font-weight: 600;
    padding: 18px 20px 19px 24.75px;
    margin-bottom: 12px;
    line-height: 16px;
    border: 1px solid #15963d;
    border-radius: 6px;
    color: #fff;
    background: linear-gradient(180deg, #80ba08 0%, #1d973d 100%);
    box-shadow: 0 2px 8px #43c05e33;
    transition: background 0.5s;
    cursor: pointer;
  }
  .cta-btn .checkmark {
    margin-right: 9.25px;
  }
  .cta-btn:hover {
    background: linear-gradient(180deg, #1d973d 0%, #80ba08 100%);
  }
  .cta-timer-label {
    font-size: 12px;
    font-weight: 450;
    line-height: 20px;
    letter-spacing: 0px;
    margin-bottom: 12px;
  }
  .cta-timer {
    font-size: 36px;
    font-weight: 400;
    line-height: 20px;
    letter-spacing: 0px;
    margin-bottom: 12px;
  }
  .cta-meta-row {
    display: flex;
    justify-content: space-between;
    align-items: center;
    width: 100%;
    background: #f5f7fa;
    border-radius: 6px;
    padding: 8px 17px 12px 17px;
    font-size: 11px;
    font-weight: 450;
  }
  .cta-meta-left,
  .cta-meta-right {
    display: flex;
    align-items: center;
  }
  .cta-meta-left {
    gap: 6px;
  }
  .cta-meta-right {
    gap: 10px;
  }
  .cta-meta-desc {
    line-height: 12px;
    letter-spacing: 0px;
  }
  .separator {
    height: 13px;
    border-left: 1px solid #012169;
  }
  .risk-high,
  .limited {
    color: #dc2c00;
    font-weight: 700;
  }
  .delivery {
    margin-left: 20px;
  }
  .free-delivery {
    font-weight: 700;
    vertical-align: middle;
  }
  .shipping {
    font-size: 12px;
    vertical-align: -1px;
  }
  @media (min-width: 900px) {
    .cta-section {
      padding: 60px 0;
    }
    .cta-mobile {
      display: none;
    }
    .cta-desktop {
      display: flex;
      flex-direction: row;
      align-items: center;
      gap: 34px;
      width: 100%;
      max-width: 920px;
      padding: 60px 38px 35px 64px;
      border-radius: 10px;
      box-shadow: 0px 0px 20px 0px #00000040;
    }
    .cta-image-wrap {
      width: 350px;
    }
    .cta-content {
      width: 417px;
      text-align: center;
    }
    .cta-headline-offer {
      width: 100%;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      gap: 4px;
      font-size: 30px;
      line-height: 35px;
      letter-spacing: -0.43px;
      margin-bottom: 8px;
    }
    .cta-desc {
      padding: 0 18px;
      margin-bottom: 12px;
    }
    .cta-btn {
      display: flex;
      align-items: center;
      justify-content: center;
      width: 100%;
      font-family: "Montserrat";
      font-size: 20px;
      font-weight: 600;
      padding: 17px 39px 20px 54px;
      line-height: 18px;
      border: 1px solid #15963d;
      border-radius: 6px;
      color: #fff;
      background: linear-gradient(180deg, #80ba08 0%, #1d973d 100%);
      box-shadow: 0 2px 8px #43c05e33;
      transition: background 0.5s;
      cursor: pointer;
    }
    .cta-timer {
      font-weight: 500;
      margin-bottom: 16px;
    }
    .cta-meta-row {
      width: 100%;
      padding: 8px 60px 12px 60px;
    }
    .delivery {
      margin-left: 0px;
    }
    .free-delivery {
      font-weight: 700;
      vertical-align: middle;
    }
    .shipping {
      font-size: 12px;
      vertical-align: -1px;
    }
  }
</style>

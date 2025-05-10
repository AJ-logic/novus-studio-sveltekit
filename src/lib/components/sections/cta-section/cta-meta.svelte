<div class="cta-meta-row">
  <span class="cta-meta-left">
    <span class="cta-icon">
      <img src="/images/icons/alert.svg" alt="Alert" loading="lazy" />
    </span>
    <span class="cta-meta-desc">
      Sell-Out Risk:
      <span class="risk-high">High</span>
    </span>
  </span>
  <span class="separator"></span>
  <span class="cta-meta-right">
    <span class="cta-icon delivery">
      <img src="/images/icons/delivery.svg" alt="Delivery" loading="lazy" />
    </span>
    <span class="cta-meta-desc">
      <span class="free-delivery">FREE</span>
      <span class="shipping"> shipping</span>
    </span>
  </span>
</div>

<style>
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
  .risk-high {
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
    .cta-meta-row {
      padding: 8px 60px 12px 60px;
    }
    .delivery {
      margin-left: 0px;
    }
  }
</style>

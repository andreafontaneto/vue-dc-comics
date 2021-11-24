<template>

  <div class="banner-info">
    <div class="container bi-content">
      <div class="bi-item">
        <img src="../assets/img/buy-comics-digital-comics.png" alt="digital-comics">
        <span>DIGITAL COMICS</span>
      </div>
      <div class="bi-item">
        <img src="../assets/img/buy-comics-merchandise.png" alt="merchandise">
        <span>DC MERCHANDISE</span>
      </div>
      <div class="bi-item">
        <img src="../assets/img/buy-comics-subscriptions.png" alt="subscriptions">
        <span>SUBSCRIPTION</span>
      </div>
      <div class="bi-item">
        <img src="../assets/img/buy-comics-shop-locator.png" alt="shop-locator">
        <span>COMIC SHOP LOCATOR</span>
      </div>
      <div class="bi-item">
        <img class="dc-power-visa" src="../assets/img/buy-dc-power-visa.svg" alt="power-visa">
        <span>DC POWER VISA</span>
      </div>
    </div>
  </div>
  
</template>

<script>
export default {
  name: 'BannerInfo'
}
</script>

<style lang="scss" scoped>

  @import "../assets/style/vars.scss";

  .banner-info{
    background-color: $blue-color;
    padding: 50px 0;

    .bi-content{
      display: flex;

      .bi-item{
        width: calc(100% / 5);
        margin: 0 10px;
        display: flex;
        justify-content: center;
        align-items: center;
        cursor: pointer;

        img{
          height: 50px;
        }

        .dc-power-visa{
          height: 30px;
        }

        span{
          color: white;
          font-size: 14px;
          margin-left: 20px;
        }
      }
    }
  }

</style>
<template>
  <footer>

    <div class="footer-top">
      <div class="container">
        <div class="content">

          <div class="footer-list">
            <div class="f-list-left">
              <h3>DC COMICS</h3>
              <ul>
                <li><a href="#">Characters</a></li>
                <li><a href="#">Comics</a></li>
                <li><a href="#">Movies</a></li>
                <li><a href="#">TV</a></li>
                <li><a href="#">Games</a></li>
                <li><a href="#">Videos</a></li>
                <li><a href="#">News</a></li>
              </ul>
              <h3>SHOP</h3>
              <ul>
                <li><a href="#">Shop DC</a></li>
                <li><a href="#">Shop DC Collectibles</a></li>
              </ul>
            </div>
            
            <div class="f-list-center">
              <h3>DC</h3>
              <ul>
                <li><a href="#">Term of Use</a></li>
                <li><a href="#">Provacy Policy (New)</a></li>
                <li><a href="#">Ad Choices</a></li>
                <li><a href="#">Advertising</a></li>
                <li><a href="#">Job</a></li>
                <li><a href="#">Subscription</a></li>
                <li><a href="#">Talent Workshop</a></li>
                <li><a href="#">CPSC Certificates</a></li>
                <li><a href="#">Ratings</a></li>
                <li><a href="#">Shop Help</a></li>
                <li><a href="#">Contact Us</a></li>
              </ul>
            </div>
            
            <div class="f-list-right">
              <h3>SITES</h3>
              <ul>
                <li><a href="#">DC</a></li>
                <li><a href="#">Mad Magazine</a></li>
                <li><a href="#">DC Kids</a></li>
                <li><a href="#">DC Universe</a></li>
                <li><a href="#">DC Power Visa</a></li>
              </ul>
            </div>
          
          </div>

          <div class="logo-big">
            <img src="../assets/img/dc-logo-bg.png" alt="logo-bg">
          </div>

        </div>
      </div>
      
    </div>   

    <div class="footer-bottom">
      <div class="container">

        <div class="footer-bottom-content">
          <button class="btn">SIGN UP NOW!</button>

          <div class="social">
            <h2>FOLLOW US</h2>
            <img src="../assets/img/footer-facebook.png" alt="f-fb">
            <img src="../assets/img/footer-twitter.png" alt="f-tw">
            <img src="../assets/img/footer-youtube.png" alt="f-yt">
            <img src="../assets/img/footer-pinterest.png" alt="f-pt">
            <img src="../assets/img/footer-periscope.png" alt="f-ps">
          </div>
        </div>
        
      </div>
    </div>   

  </footer>
</template>

<script>
export default {
  name: 'Footer'
}
</script>

<style lang="scss" scoped>

  @import "../assets/style/vars.scss";

  footer{
    // height: 350px;
    // padding-bottom: 40px;

    .footer-top{
      background-image: url(../assets/img/footer-bg.jpg);
      background-size: cover;
      background-position: center;
      background-repeat: no-repeat;

      .content{
        height: 350px;
        display: flex;
        overflow: hidden;

        .footer-list{
          width: 30%;
          padding: 20px 0 40px 0;
          display: flex;
          justify-content: space-between;

          h3{
            color: white;
            padding: 15px 0;
          }

          ul{
            list-style: none;

            li a{
              text-decoration: none;
              color: #747474;
              font-size: 12px;
            }
          }
        }

        .logo-big{
          margin-left: auto;

          img{
            width: 540px;
            position: relative;
            bottom: 100px;
          }
        }
      }

    }

    .footer-bottom{
      width: 100%;
      background-color: $dark-grey-color;
      padding: 30px 0;

      .footer-bottom-content{
        display: flex;

        .btn{
          background-color: $dark-grey-color;
          border: 3px solid $blue-color;
          color: white;
          font-size: 15px;
          padding: 15px;
          cursor: pointer;
        }

        .social{
          display: flex;
          align-items: center;
          margin-left: auto;

          h2{
            font-size: 18px;
            color: $blue-color;
            margin-right: 30px;
          }

          img{
             margin: 0 10px;
             cursor: pointer;
          }
        }
      }  
    }
  }

</style>
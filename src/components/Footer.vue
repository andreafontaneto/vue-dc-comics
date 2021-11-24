<template>
  <footer>
    <div class="container">

      <div class="footer-top">
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

      <div class="footer-bottom">

      </div>
      

      

    </div>
  </footer>
</template>

<script>
export default {
  name: 'Footer'
}
</script>

<style scoped>

  footer{
    height: 350px;
    background-image: url(../assets/img/footer-bg.jpg);
    background-size: cover;
    background-position: center;
    background-repeat: no-repeat;
    padding: 20px 0 40px 0;
    overflow: hidden;
  }

  .footer-top{
    display: flex;
  }

  .footer-list{
    width: 30%;
    display: flex;
    justify-content: space-between;
  }

  h3{
    color: white;
    padding: 15px 0;
  }

  ul{
    list-style: none;
  }

  li a{
    text-decoration: none;
    color: #747474;
    font-size: 12px;
  }

  .logo-big{
    width: 510px;
    margin-left: auto;
  }

  img{
    position: relative;
    bottom: 100px;
  }

</style>
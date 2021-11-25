<template>
  <main>
    
    <div class="jumbotron">
      <img src="../assets/img/jumbotron.jpg" alt="jumbotron">
    </div>
    
    <div class="container">
      
      <div class="current-series">
        <h5>CURRENT SERIES</h5>
      </div>

      <div class="cards-box">
        
        <div class="card">
          
          <div class="card-img">
            <img src="https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/AC1000_DLX_162-001_HD_5ba13723281ab0.37845353.jpg?itok=ZsI-C5eX" alt="x">
          </div>

          <div class="card-title">
            <p>NOME CARD</p>
          </div>
          
        </div>
        <div class="card">
          
          <div class="card-img">
            <img src="https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/AC1000_DLX_162-001_HD_5ba13723281ab0.37845353.jpg?itok=ZsI-C5eX" alt="x">
          </div>

          <div class="card-title">
            <p>NOME CARD</p>
          </div>
          
        </div>
        <div class="card">
          
          <div class="card-img">
            <img src="https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/AC1000_DLX_162-001_HD_5ba13723281ab0.37845353.jpg?itok=ZsI-C5eX" alt="x">
          </div>

          <div class="card-title">
            <p>NOME CARD</p>
          </div>
          
        </div>
        <div class="card">
          
          <div class="card-img">
            <img src="https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/AC1000_DLX_162-001_HD_5ba13723281ab0.37845353.jpg?itok=ZsI-C5eX" alt="x">
          </div>

          <div class="card-title">
            <p>NOME CARD</p>
          </div>
          
        </div>
        <div class="card">
          
          <div class="card-img">
            <img src="https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/AC1000_DLX_162-001_HD_5ba13723281ab0.37845353.jpg?itok=ZsI-C5eX" alt="x">
          </div>

          <div class="card-title">
            <p>NOME CARD</p>
          </div>
          
        </div>
        <div class="card">
          
          <div class="card-img">
            <img src="https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/AC1000_DLX_162-001_HD_5ba13723281ab0.37845353.jpg?itok=ZsI-C5eX" alt="x">
          </div>

          <div class="card-title">
            <p>NOME CARD</p>
          </div>
          
        </div>
        <div class="card">
          
          <div class="card-img">
            <img src="https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/AC1000_DLX_162-001_HD_5ba13723281ab0.37845353.jpg?itok=ZsI-C5eX" alt="x">
          </div>

          <div class="card-title">
            <p>NOME CARD</p>
          </div>
          
        </div>

      </div>

      <div class="load">
        <button class="load-btn">LOAD MORE</button>
      </div>



    </div>
  
  </main>
</template>

<script>
export default {
  name: 'Main'
}
</script>

<style lang="scss" scoped>

  @import "../assets/style/vars.scss";

  main {
    background-color: #151515;
    color: white;
    font-size: 30px;

    .jumbotron {
      height: 400px;
      background-color: cornflowerblue;
      overflow: hidden;
    }

    .current-series{
      width: 220px;
      padding: 20px;
      font-size: 25px;
      color: white;
      background-color: $blue-color;
      display: flex;
      justify-content: center;
      align-items: center;
    }

    .cards-box{
      display: flex;
      flex-wrap: wrap;

      .card{
        width: calc((100% / 6) - 20px);
        margin: 20px;

        .card-img{
          width: 100%;
          height: 180px;
          overflow: hidden;
          cursor: pointer;
        }

        .card-title p{
          font-size: 14px;
          color: grey;
          margin: 10px 0;
          cursor: pointer;
        }
        
      }
    }

    .load{
      display: flex;
      justify-content: center;
      padding: 20px 0;

      .load-btn{
        background-color: $blue-color;
        color: white;
        font-size: 13px;
        font-weight: 700;
        padding: 10px 50px;
        border: none;
        cursor: pointer;    
      }
    }
    
  }

</style>
<template>
  <header class="container">

    <div class="logo">
       <img src="../assets/img/dc-logo.png" alt="logo">
    </div>

    <ul>
      <li><a href="#">Characters</a></li>
      <li><a href="#">Comics</a></li>
      <li><a href="#">Movies</a></li>
      <li><a href="#">Tv</a></li>
      <li><a href="#">Games</a></li>
      <li><a href="#">Collectibles</a></li>
      <li><a href="#">Videos</a></li>
      <li><a href="#">Fans</a></li>
      <li><a href="#">News</a></li>
      <li><a href="#">Shop</a></li>
    </ul>

  </header>
</template>

<script>
export default {
  name: 'Header',
  data(){
    return{
      menuLinks: [

        {
          url: '/characters',
          text: 'Characters',
          current: false
        },
        {
          url: '/comics',
          text: 'Comics',
          current: true
        },{
          url: '/movies',
          text: 'Movies',
          current: false
        },{
          url: '/tv',
          text: 'Tv',
          current: false
        },{
          url: '/games',
          text: 'Games',
          current: false
        },{
          url: '/collectibles',
          text: 'Collectibles',
          current: false
        },{
          url: '/videos',
          text: 'Videos',
          current: false
        },{
          url: '/fans',
          text: 'Fans',
          current: false
        },{
          url: '/news',
          text: 'News',
          current: false
        },{
          url: '/shop',
          text: 'Shop',
          current: false
        }

      ]
    }
  }
}
</script>

<style scoped>

  header{
    height: 100px;
    background-color: white;
    display: flex;
    align-items: center;
  }

  .logo{
    width: 80px;
    height: 80px;
  }

  ul{
    list-style: none;
    display: flex;
    margin-left: auto;
  }

  a{
    text-decoration: none;
    text-transform: uppercase;
    font-size: 12px;
    font-weight: 700;
    color: grey;
    padding: 36px 12px;
  }

  a:hover{
    color: #176DF3;
    border-bottom: 5px solid #176DF3;
  }

</style>
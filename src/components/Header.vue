<template>
  <header class="container">

    <div class="logo">
       <img src="../assets/img/dc-logo.png" alt="logo">
    </div>

    <ul>
      <li v-for="(link, index) in menuLinks" :key="index">
        <a :class="{active: link.current === true}" href="link.url">{{link.text}}</a>
      </li>
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

  a.active{
    border-bottom: 5px solid #176DF3;
  }

  a:hover{
    color: #176DF3;
    border-bottom: 5px solid #176DF3;
  }

</style>
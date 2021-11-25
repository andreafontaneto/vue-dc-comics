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
        
        <!-- <CardBox
        v-for="(card, index) in cardsList"
        :key ="index"
        :thumb="card.thumb"
        :series="card.series"
        /> -->

        <CardBox
        v-for="(card, index) in cardData"
        :key ="index"
        :card="card"
        />

      </div>

      <div class="load">
        <button class="load-btn">LOAD MORE</button>
      </div>



    </div>
  
  </main>
</template>

<script>

import CardBox from './CardBox';
import cardData from '../assets/data/cardData.js';

export default {
  name: 'Main',

  components:{
    CardBox
  },

  data(){
    return{
      cardData
    }
  }
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
      width: 250px;
      padding: 15px 20px;
      font-size: 30px;
      color: white;
      background-color: $blue-color;
      display: flex;
      justify-content: center;
      align-items: center;
      position: relative;
      bottom: 30px;
    }

    .cards-box{
      display: flex;
      flex-wrap: wrap;
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
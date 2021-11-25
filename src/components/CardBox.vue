<template>
  
  <div class="card">
          
    <div class="card-img">
      <img :src="thumb" :alt="series">
    </div>

    <div class="card-title">
      <p>{{series}}</p>
    </div>
          
  </div>

</template>

<script>
export default {
  name: 'CardBox',

  props:{
    thumb: String,
    price: String,
    series: String,
    type: String
  }

}
</script>

<style lang="scss" scoped>

@import "../assets/style/vars.scss";

.card{
  width: calc((100% / 6) - 30px);
  margin: 15px;

  .card-img{
    width: 100%;
    height: 180px;
    overflow: hidden;
    cursor: pointer;
  }

  .card-title p{
    font-size: 14px;
    color: white;
    text-transform: uppercase;
    margin: 15px 0;
    cursor: pointer;
  }
        
}

</style>
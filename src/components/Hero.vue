<template>
  <div class="jumbotorn">
    <div class="container">
      <div class="photoContainer">
        <img src="https://images-na.ssl-images-amazon.com/images/I/91FXOwXDnoL.jpg" alt="">
      </div>
       <div class="photoContainer">
        <img src="https://m.media-amazon.com/images/I/81VIte-lt7L._SL1500_.jpg" alt="">
      </div>
       <div class="photoContainer">
        <img src="https://m.media-amazon.com/images/I/710W06zfvVL._AC_SY679_.jpg" alt="">
      </div>
       <div class="photoContainer">
        <img src="https://i.pinimg.com/originals/fd/38/d0/fd38d0c436dec6077fe341b74f05c2d7.jpg" alt="">
      </div>

    </div>
  </div>
</template>

<script>
export default {
  name: 'Hero'
}
</script>
<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.jumbotorn{
  display: flex;
  justify-content: center;
  align-items: center;

}
.container {
  height: 300px;
  width: 500px;
  display: flex;
}

.photoContainer{
  width: calc(100% / 4);
  height: 100%;
  overflow: hidden;

}

img{
  height: 100%;

}

</style>

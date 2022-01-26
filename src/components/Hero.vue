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
      <div class="cover">
        <div class="marvel"><strong>MARVEL</strong></div>
        <button>Watch now!</button>
      </div>
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
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
.jumbotorn{
  display: flex;
  justify-content: center;
  align-items: center;
  width: 100%;

}
.container {
  height: 400px;
  width: 60%;
  display: flex;
  position: relative;
  
}

.photoContainer{
  width: calc(100% / 4);
  height: 100%;
  overflow: hidden;

}

img{
  height: 100%;

}

.cover{
  background-color: rgba(0, 0, 0, 0.281);
  position: absolute;
  top: 0;
  left: 0;
  bottom: 0;
  right: 0;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
}

.marvel{
  color:white;
  font-size: 75px;
  background-color: red;
  padding: 30px;
  width: 400px;
}

button{
  border-radius: 20px;
  padding: 10px;
  margin: 20px;
  background-color: gray;
}



</style>

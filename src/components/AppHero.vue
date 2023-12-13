<template>
  <div class="jumbotron">
    <h2>{{ msg }}</h2>
    <div class="box">
      <img src="../assets/DSC_9063.jpg" alt="jumbo">
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      msg: 'jumbotron',
    }
  }
}
</script>

<style>
.jumbotron {

  height: 600px;
  background-position: center;
  background-repeat: no-repeat;
  background-image: url(../assets/DSC_9063.jpg);
}
.jumbotron h2{
  color: rgba(255, 255, 255, 0.7);
  font-size: 4rem;
  padding-top: 2rem;
  text-transform: uppercase;
}
.box {
  height: 400px;
  width: 95%;
  margin: auto;
  box-shadow: 0 0 20px 20px rgba(0, 0, 0, 0.6);
}
img{
  height: 100%;
}
</style>
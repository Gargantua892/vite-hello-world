<script setup>

</script>

<template>
  <div>
    <div class="hero">
      <div class="description">
        <h5>Cover story</h5>
        <h2>8 best ideas for a spring autumn break in Corfu</h2>
        <a href="#" class="cta">Discover It</a>
      </div>
      <div class="img-container">
        <img src="../assets/openairathens_2022.webp" alt="">
      </div>
    </div>
  </div>
</template>
<style scoped>
  .hero{
    position: relative;
    display: flex;
    width: 100%;
    background-color: #fff;
  }

  h2{
    margin: 0px 0px 24px 0px;
  }

  h5{
    color: orange;
    margin: 8px 0px;
    text-transform: uppercase;
  }


  .description{
    background-color: #fff;
    color: #000;
    text-align: left;
    position: absolute;
    max-width: 40%;
    top: 4rem;
    left: 64px;
    padding: 36px;
  }
  .img-container {
    width: 100%;
    height: 100vh;
    overflow: hidden;
  }

  .img-container img{
    width: 100%;
    height: 100%;
    object-fit: cover;
    padding-left: 20%;
  }
</style>

<template>
  <div  class="main wrapper">
    <div main__top>
      <img src="../assets/hear.jpeg" alt="" class="main__top__img">
      <div class="main__top__logo">
        <h2 class="main__top__logo__title">
          HAIR  SALON
        </h2>
        <h3 class="main__top__logo__name">
          Beauty
        </h3>
      </div>
    </div>
    <div>

    </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

  .main {

  }

  .wrapper {
    padding: 0 4%;
    margin: 0 auto;
    max-width: 1200px;
  }

  .main__top {

  }

  .main__top__img {

  }

  .main__top__logo {
    position: absolute;
    bottom: 0px;
    right: 200px;
    color: white;
  }

  .main__top__logo__title {
    
  }

  .main__top__logo__name {
    font-family: cursive;
  }
</style>

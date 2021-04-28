<template>
  <header class="page__header wrapper"> 
    <div class="header__left">
      <div class="header__left__logo">
        Beauty
      </div>
    </div>
    <nav class="header__right">
      <ul class="header__right__list">
        <li>
          HOME
        </li>
        <li>
          MENU
        </li>
        <li>
          ACCESS
        </li>
      </ul>
    </nav>  
  </header>
</template>
<script>
export default {
  name: 'Header',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  
  .page__header { 
    width: 100%;
    display: flex;
    justify-content: space-between;
  }

  .wrapper {
    margin: 0 auto;
    padding: 0 4%;
    max-width: 1100px;
  }

  .header__left {
    /* width: 340px; */
    font-family: cursive;
    font-size: 60px;
    color: black;
    margin-top: 8px;
  }

  .header__right__list {
    display: flex;
    justify-content: space-between;
    margin-top: 50px;
    list-style: none;
    color: black;
    font-size: 1.25rem;
  }

  .header__right__list li {
    margin-left: 36px;
   
  }


</style>

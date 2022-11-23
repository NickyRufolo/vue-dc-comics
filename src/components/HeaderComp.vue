<template>
  <header>
    <div class="img">
      <img src = "../assets/dc-logo.png" alt = "Test Image" />
    </div>
    <nav class="nav-lista">
        <div><h4>CHARACTERS</h4></div>
        <div><h4 id="comics">COMICS</h4></div>
        <div><h4>MOVIES</h4></div>
        <div><h4>TV</h4></div>
        <div><h4>GAMES</h4></div>
        <div><h4>COLLECTIBLES</h4></div>
        <div><h4>FANS</h4></div>
        <div><h4>NEWS</h4></div>
        <div><h4>SHOP</h4></div>
    </nav>
  </header>
</template>

<script>
export default {
  name: `HeaderComp`,
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
@import "../style/variabili.scss"; //mi richiamo la variabile nello style 

header{
  background-color: white;
  max-height: 120px;
  display: flex;
  justify-content: space-between;
  align-items: center;
  @include center;
}
.nav-lista {
  display: flex;
  background-color: white;
  justify-content: space-around;
}
h4 {
  margin: 10px
}
#comics {
  color:#1187F9;
}
</style>

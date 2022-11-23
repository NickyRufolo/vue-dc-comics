<template>
<div>
<footer>
    <div class="parte-final">
<div class="last-lista1">
    <ul> <h5>DC COMICS</h5>
        <li>Characters</li>
        <li>Comics</li>
        <li>Movies</li>
        <li>TV</li>
        <li>GAMES</li>
        <li>VIDEOS</li>
        <li>NEWS</li>
    </ul>
    <br>
        <ul> <h5>DC COMICS</h5>
        <li>Characters</li>
        <li>Comics</li>
        <li>Movies</li>
    </ul>
</div>
<div class="last-lista2">
    <ul> <h5>DC COMICS</h5>
        <li>Characters</li>
        <li>Comics</li>
        <li>Movies</li>
        <li>TV</li>
        <li>GAMES</li>
        <li>VIDEOS</li>
        <li>NEWS</li>
    </ul>
</div>
<div class="last-lista3">
    <ul> <h5>DC COMICS</h5>
        <li>Characters</li>
        <li>Comics</li>
        <li>Movies</li>
        <li>TV</li>
        <li>GAMES</li>
        <li>VIDEOS</li>
        <li>NEWS</li>
    </ul>
</div>
    <div>
        <img id="logoFoot" src="../assets/dc-logo-bg.png" alt="">
    </div>
</div>
</footer>
<LastFooter/>
</div>
</template>

<script>
import LastFooter from './LastFooter.vue'

export default {
    name: 'FooterComp',
    components: {
    LastFooter
    }
}
</script>

<style scoped lang="scss">
@import "../style/variabili.scss"; //mi richiamo la variabile nello style 
footer {
width: 100%;
height: 400px;
background-image:url("../assets/footer-bg.jpg");
background-repeat: no-repeat;
background-size: cover;
color: $color-gold;}

.last-lista1 {
    margin-top: 20px;
    margin-right: 15px;

}
.last-lista2 {
        margin-top: 20px;
        margin-right: 15px;


}
.last-lista3 {
    margin-top: 20px;
    margin-right: 15px;

}
.parte-final {
@include center;
    display: flex;

}
#logoFoot {
    height: 100%;
    margin-left: 300px;
    margin-top: -50px;
}
li {
text-align: left;
font-size: 0.8rem;
}
h5 {
    padding: 12px 0;
}
</style>
<template>
<div>
<footer>
    <div class="parte-final">
<div class="last-lista1">
    <ul>
        <h5>DC COMICS</h5>
        <li>Characters</li>
        <li>Comics</li>
        <li>Movies</li>
        <li>TV</li>
        <li>GAMES</li>
        <li>VIDEOS</li>
        <li>NEWS</li>
    </ul>
    <ul>
        <h5>DC COMICS</h5>
        <li>Characters</li>
        <li>Comics</li>
        <li>Movies</li>
    </ul>
</div>
<div class="last-lista2">
    <ul>
        <h5>DC COMICS</h5>
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
    <ul>
        <h5>DC COMICS</h5>
        <li>Characters</li>
        <li>Comics</li>
        <li>Movies</li>
        <li>TV</li>
        <li>GAMES</li>
        <li>VIDEOS</li>
        <li>NEWS</li>
    </ul>
</div>
    <div id="logoFoot">
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
height: 315px;
background-image:url("../assets/footer-bg.jpg");
background-repeat: no-repeat;
background-size: cover;
color: $color-gold;}

.last-lista1 {
    margin-right: 15px;

}
.last-lista2 {
    margin-right: 15px;

}
.last-lista3 {
    margin-right: 15px;
}
.parte-final {
@include center;
    display: flex;
    justify-content: space-between;

}
#logoFoot {
background-image: url("../assets/dc-logo-bg.png");
background-repeat: no-repeat;
background-position: center;
background-size: cover;
width: 40%;

}
li {
text-align: left;
font-size: 0.8rem;
list-style: none;

}

</style>
<template>
<main>
    <div class="black">
    <div class="main-black">
        <div><h3 id="contentText">...Contents goes here!...</h3></div>
    </div>
    </div>
    <div class="blu-100">
    <div class="main-blue">
            <div class="a">
                <img id="img1" src = "../assets/buy-comics-digital-comics.png"/>
                <span class="text-in-blu">DIGITAL COMICS</span>
            </div>
                        <div class="a">
                <img id="img1" src = "../assets/buy-comics-digital-comics.png"/>
                <span class="text-in-blu">DIGITAL COMICS</span>
            </div>
                        <div class="a">
                <img id="img1" src = "../assets/buy-comics-digital-comics.png"/>
                <span class="text-in-blu">DIGITAL COMICS</span>
            </div>
                        <div class="a">
                <img id="img1" src = "../assets/buy-comics-digital-comics.png"/>
                <span class="text-in-blu">DIGITAL COMICS</span>
            </div>
                        <div class="a">
                <img id="img1" src = "../assets/buy-comics-digital-comics.png"/>
                <span class="text-in-blu">DIGITAL COMICS</span>
            </div>
    </div>
</div>
</main>
</template>


<script> 
export default {
    name: `MainComp`,
}
</script>

<style scoped lang="scss">
@import "../style/variabili.scss"; //mi richiamo la variabile nello style 

.blu-100 {
    background-color:#1187F9;
    width: 100%;
    margin: auto;
}
.black {
    background-color: black;
    width: 100%;
    margin: auto;
}
.main-black{
    height: 150px;
    display: flex;
    align-items: center;
@include center;
}
#contentText {
    color: white;
    font-size: 1.8rem;
    
}
.main-blue{
    width: 80%;
    margin: auto;
    height: 120px;
    display: flex;
    justify-content: space-between;
    align-items: center;
    @include center;
}
#img1{
    width: 40px;
    height: 60px;
}
.text-in-blu
{color:white;
    margin-left: 10px;
    font-size: 0.85rem;
}
.a {
    display: flex;
    align-items: center;
}
</style>
<template>
    <div>
        <img :src="dettagliFumetto.thumb" alt=""> 
        <!-- //attribbutto virgolette -->
        <span> {{dettagliFumetto.series}} </span>
    </div>
</template>


<script> 
export default {
    name: `FumettoCard`,
    props: {
        dettagliFumetto: Object
    }
}
</script>


<style scoped lang="scss">

div {
    width: calc( 100% / 7 );
    color: whitesmoke;
    padding: 10px 10px;
}
img {
    width: auto;
}
</style>
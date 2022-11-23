<template>
    <div class="grey-footer">
        <div class="div-grey">
        <div>
            <button>SIGN-UP NOW!</button>
        </div>
        <div class="loghi">
            <div> <h3 id="followus">FOLLOW US</h3></div>
            <div><img src="../assets/footer-facebook.png" alt=""></div>
            <div><img src="../assets/footer-periscope.png" alt=""></div>
            <div><img src="../assets/footer-pinterest.png" alt=""></div>
            <div><img src="../assets/footer-twitter.png" alt=""></div>
            <div><img src="../assets/footer-youtube.png" alt=""></div>
        </div>
    </div>
    </div>
</template>

<script> 
export default {
    name: `LastFooter`,
}

</script>



<style scoped lang="scss">
.grey-footer{
    background-color: #2C2B2C;
    width: 100%;
    height: 70px;
    padding: 15px 0;
}
.div-grey{
    display: flex;
    justify-content: space-between;
    align-items: center;
    width: 80%;
    margin-left: 135px;

}
.loghi{
display: flex;
align-items: center;
}
#followus {
color: #1187F9;
padding: 0 10px}

.loghi,img {
        padding: 0 5px;
}
</style>

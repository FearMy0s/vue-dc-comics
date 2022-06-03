<template class="main-tb">
    <main class="main">
    <div class="container-main"> 
        <h1>Lorem ipsum dolor sit amet consectetur adipisicing elit. Error, repellendus tempore, perspiciatis accusantium omnis accusamus reiciendis eveniet alias placeat quibusdam nobis porro saepe ducimus earum sed ab animi nostrum unde.</h1>
    </div>
    <div class="container-main-2">
        <div class="img-container-main">
            <img src="../assets/img/buy-comics-digital-comics.png" alt="">
            <span>DIGITAL COMICS</span>
            <img src="../assets/img/buy-comics-merchandise.png" alt="">
            <span>MERCHANDISE</span>
            <img src="../assets/img/buy-comics-shop-locator.png" alt="">
            <span>COMICS SHOP LOCATION</span>
            <img src="../assets/img/buy-comics-subscriptions.png" alt="">
            <span>SUBSCRIPTION</span>
            <img src="../assets/img/buy-dc-power-visa.svg" alt="">
            <span>DC POWER VISA</span>
        </div>
    </div>  
    </main>
</template>

<script>
export default {
name: 'DCmain',
}
</script>

<style>
@import '../assets/style/mixins.scss';
    .container-main h1{
        padding-top: 65px;
        color: white;
        font-size: 25px;
    }
    .container-main-2 img{
        vertical-align: middle;
        width: 50px;
        height: 70px;
        margin-top: 50px;
    }
    .container-main-2 span{
        padding-top:45px ;
        vertical-align: middle;
        font-size: 15px;
        margin-left: 20px;
        margin-right:80px;
        color: white;
    }
</style>
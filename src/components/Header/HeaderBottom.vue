<script setup lang="ts">
import Cart from './Cart.vue';
</script>

<template>
    
        <div class="container header-bottom">
            <div class="row">
                <!--Logo-->
                <div class="col-2 d-flex justify-content-start">
                    <div class="header-logo">
                        <img src="../../assets/logo.svg" alt="">  
                    </div>
                </div>

                <!--Offer-->
                <div class="col-6 d-flex services">
                    <div class="services1">
                        <div class="services-item border-end">
                            <div class="services-item_icon"></div>
                            <span class="services-item_title">Free Shipping <br> product</span>
                        </div>
                    </div>
                    <div class="services2">
                        <div class="services-item border-end">
                            <div class="services-item_icon"></div>
                            <span class="services-item_title">Money Back <br> Guarantee</span>
                        </div>
                    </div>
                    <div class="services3">
                        <div class="services-item">
                            <div class="services-item_icon"></div>
                            <span class="services-item_title">Special Weekly <br> Offer</span>
                        </div>
                    </div>
                </div>

                <!--Cart, contact, input-->
                <Cart></Cart>
            </div>
    </div>
</template>

<style scoped>
    .header-bottom {
        position: relative;
        width: 100%;
        text-align: center;
        padding: 0;
        margin: 0 auto; 
    }

    .services{
        margin-left: 14px;
        margin-top: 35px;
    }

    .header-logo {
        padding: 35px 0 20px;
        /* width: 165px; */
    }
    .services-item{
        padding: 0 25px;
    }

    .services1 .services-item .services-item_icon{
        background: url(../../assets/truck.svg) no-repeat scroll center;
        height: 36px;
        width: 40px;
        float: left;
        margin-right: 5px;
    }
    .services2 .services-item .services-item_icon{
        background: url(../../assets/Money.svg) no-repeat scroll center;
        height: 36px;
        width: 40px;
        float: left;
        margin-right: 5px;
    }
    .services3 .services-item .services-item_icon{
        background: url(../../assets/Offer.svg) no-repeat scroll center;
        height: 36px;
        width: 40px;
        float: left;
        margin-right: 5px;
    }

    .services-item_icon{
        margin-top: 2px;
    }

    .services-item_title{
        font-size: 14px;
        line-height: 18px;
        letter-spacing: 0;
        text-transform: capitalize;
        text-align: left;
        font-weight: 400;
        color: #777;
    }

    
</style>
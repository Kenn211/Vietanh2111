<script setup lang="ts">
    function alertButton() {
        alert('Cái này chưa làm ạ =))');    
    }
</script>

<template>
    <div class="col d-flex flex-column">
        <!--Contact, Cart-->
        <div class="d-flex contact-and-cart justify-content-end"> 
            <div class="contact d-flex">
                <div class="contact-icon"></div>
                <div class="contact-phone">
                    <span>(+84) 987 049 481</span>
                </div>
            </div>

            <div class="cart-custom">
                <div class="cart d-flex">
                    <div class="cart-basket">
                        <div class="cart-basket-item">
                            <span class="cart-basket-item_amount">0</span>
                        </div>
                    </div>

                    <div class="cart-price">
                        <span class="cart-price_title">Item -</span>
                        <span class="cart-price_price"> $0.00</span>
                    </div>
                </div>
            </div>
        </div>


        <!--Input-->
        <div class="input-custom d-flex">
            <div class="input-search">
                <input type="text" class="form-control" placeholder="Search for all product..." />
            </div>
            <button @click="alertButton()" type="submit" class="btn btn-default btn-search">
                    <span>Search</span>
            </button>
        </div>
    </div>
</template>

<style scoped>
    .cart-custom {
        padding: 5px 0;
        z-index: 7;
        float: right;
        position: relative;
        cursor: pointer;
        margin: 0;
        margin-right: 0;
    }
    .contact {
        position: relative;
        width: auto;
        float: right;
        margin: 8px 0;
    }

    .contact-phone {
        float: left;
        position: relative;
        padding: 10px 0 0;
        font-size: 14px;
        line-height: 18px;
        letter-spacing: 0.2px;
        font-weight: 500;
        color: #777;
    }
    .contact-icon {
        background: url(../../assets/call.svg) no-repeat scroll center;
        background-size: 20px;
        height: 37px;
        width: 37px;
        float: left;
        margin-right: 0px;
    }

    .cart-basket-item {
        background: url(../../assets/basket.svg) no-repeat scroll center;
        margin: 8px 12px 0 15px;
        height: 28px;
        width: 28px;
        float: left;
        background-size: 28px;
        position: relative;
    }
    
    .cart-basket-item_amount{
        position: absolute;
        height: 26px;
        width: 26px;
        right: auto;
        color: #777;
        line-height: 18px;
        font-size: 14px;
        font-weight: 500;
        top: auto;
        left: 20px;
        bottom: -3px;
    }

    .cart-price {
        margin-top: 10px;
        font-size: 14px;
    }
    .cart-price_title {
        font-size: 14px;
        position: relative;
        padding-right: 0px;
        text-transform: capitalize;
        line-height: 21px;
        font-weight: 500;
        color: #777;
    }

    .cart-price_price{
        font-size: 14px;
        letter-spacing: 0.5px;
        color: #777;
        font-weight: 500;
        margin-top: 0;
        line-height: 21px;
    }

    .input-custom {
        position: relative;
        background: #C2D82E;
        padding: 8px;
        width: 100%;
        border-radius: 5px 5px 0 0;
    }

    .input-search{
        border-radius: 5px;
        color: #2e2e2e;
        height: 38px;
        margin: 0;
        width: 100%;
    }
    .btn-search{
        background-color: #e75c49;
        border: medium none;
        color: #fff;
        height: 38px;
        padding: 6px 17px;
        position: relative;
        text-align: center;
        border-radius: 5px;
        font-weight: 400;
        line-height: 18px;
        margin-left: 5px;
    }
</style>
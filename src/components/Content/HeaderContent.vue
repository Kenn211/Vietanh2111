<script setup lang="ts">

</script>

<template>

        <div class="container content rounded">
            <div class="row"> 
                    <!--Category-services-->
                    <div class="category-product col-4">
                        <div class="category-product-block">
                            <div class="block-title">
                                <div class="block-menu_title">Shop by Categories</div>
                            </div>

                            <div class="block-menu">
                                
                            </div>
                        </div>
                    </div>
                    <!--category-services-->
                    <div class="category-services d-flex col-8">
                        <ul class="nav">
                            <li class="nav-item">
                                <a class="nav-link-item border-end border-3" href="#">Home</a>
                            </li>
                            <li class="nav-item ">
                                <a class="nav-link-item border-end border-3" href="#">Price Drop</a>
                            </li>
                            <li class="nav-item">
                                <a class="nav-link-item border-end border-3" href="#">Best Sales</a>
                            </li>
                            <li class="nav-item">
                                <a class="nav-link-item border-end border-3" href="#">Delivery</a>
                            </li>
                            <li class="nav-item">
                                <a class="nav-link-item border-end border-3" href="#">About Us</a>
                            </li>
                            <li class="nav-item">
                                <a class="nav-link-item" href="#">Contact Us</a>
                            </li>
                        </ul>                    
                </div>
            </div>
        </div>

</template>

<style scoped>
    .content {
        position: relative;
        height: auto;
        background-color: #f0f0f0;
        width: 100%;
        text-align: center;
        padding: 0;
        margin: 0 auto; 
        z-index: 9;
    }

    .category-product{
        width: 20%;
        padding: 0;
        margin-left: 10px;
    }

    .category-services {
        align-items: center;
    }

    .nav-link-item {
        display: block;
        padding: 0.7rem 1rem;
        color: #0d6efd;
        text-decoration: none;
        transition: color .15s ease-in-out,background-color .15s ease-in-out,border-color .15s ease-in-out;
        color: #333;
    }
    .category-product-block{
        /* display: inline-block; */
        /* vertical-align: top; */
        /* float: none; */
        background: #e5e5e5;
        border-radius: 5px;
        text-align: left;
        clear: both;
        cursor: pointer;
    }
    
    .block-title {
        border-bottom: none;
        float: left;
        position: relative;
        transition: all 500ms ease 0s;
        /* -webkit-transition: all 500ms ease 0s; */
        -moz-transition: all 500ms ease 0s;
        -ms-transition: all 500ms ease 0s;
        -o-transition: all 500ms ease 0s;
        padding: 3px 4px 0;
        color: #333333;
        width: 94%;
        padding: 9px 13px;
        cursor: pointer;
        border-radius: 5px;
        margin-top: 5px;
        margin-bottom: 5px;
        margin-left: 7px;
        background: #e76453;
    }
    
    .block-menu_title {
        color: #fff;
        cursor: pointer;
        font-size: 14px;
        font-weight: 500;
        letter-spacing: 0.3px;
        line-height: 20px;
        overflow: hidden;
        position: relative;
        text-transform: capitalize;
        width: auto;
    }
</style>
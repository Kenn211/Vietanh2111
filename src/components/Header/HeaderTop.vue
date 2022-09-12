<script setup lang="ts">
import {reactive,ref} from "vue";

const selectCurrentCy = reactive({
        
})

const focusItemChangeColor = ref({
    changeColor: true,
})

</script>

<template>
    <nav class="header-top">
        <div class="container">
            <div class="row">
                <div class="left-nav col-4">
                    <ul class="nav justify-content-start left-nav-item">
                        <li class="nav-item-icon-left">
                            <a class="nav-link text-muted" href="#"><i class="fab fa-facebook-f"></i></a>
                        </li>
                        <li class="nav-item-icon-left">
                            <a class="nav-link text-muted" href="#"><i class="fab fa-instagram"></i></a>
                        </li>
                        <li class="nav-item-icon-left">
                            <a class="nav-link text-muted" href="#"><i class="fab fa-twitter"></i></a>
                        </li>
                        <li class="nav-item-icon-left">
                            <a class="nav-link text-muted" href="#"><i class="fab fa-youtube"></i></a>
                        </li>
                        <li class="nav-item-icon-left">
                            <a class="nav-link text-muted" href="#"><i class="fab fa-pinterest-p"></i></a>
                        </li>
                    </ul>
                </div>

                <div class="right-nav col-8">
                    <ul class="nav justify-content-end right-nav-item">
                        <li class="nav-item">
                            <a class="nav-link text-muted nav-item-right border-end" href="#">Store Locatar</a>
                        </li>
                        <li class="nav-item ">
                            <a class="nav-link text-muted nav-item-right border-end" href="#">Compare</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link text-muted nav-item-right border-end" href="#">WishList</a>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link text-muted dropdown-toggle nav-item-right border-end" data-bs-toggle="dropdown" href="#">Currency</a>
                            <ul class="dropdown-menu">
                                <li><a class="dropdown-item" href="#"><i class="fab fa-euro-sign"></i>EUR</a></li>
                                <li><a class="dropdown-item" href="#"><i class="fab fa-dollar-sign"></i>USD</a></li>
                            </ul>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link nav-item-right text-muted dropdown-toggle border-end" data-bs-toggle="dropdown" href="#">Language</a>
                            <ul class="dropdown-menu">
                                <li><a class="dropdown-item" href="#"><img class="px-2" src="../../assets/united-states-of-america.png" />English</a></li>
                                <li><a class="dropdown-item" href="#"><img class="px-2" src="../../assets/united-states-of-america.png" />India</a></li>
                                <li><a class="dropdown-item" href="#"><img class="px-2" src="../../assets/united-states-of-america.png" />Spain</a></li>
                                <li><a class="dropdown-item" href="#"><img class="px-2" src="../../assets/united-states-of-america.png" />Italia</a></li>
                                <li><a class="dropdown-item" href="#"><img class="px-2" src="../../assets/united-states-of-america.png" />France</a></li>
                            </ul>
                        </li>
                        <li class="nav-item">
                            <a class="nav-link nav-item-right text-muted dropdown-toggle" data-bs-toggle="dropdown" href="#">My Account</a>
                            <ul class="dropdown-menu">
                                <li><a class="dropdown-item" href="#">Sign In</a></li>
                            </ul>
                        </li>
                    </ul>
                </div>
            </div>  
        </div>  
    </nav>
</template>

<style Scope>
.header-top {
    height: auto;
    width: 100%;
    background-color: #f0f0f0;
}

.left-nav-item li {
    color: #333;
    opacity: 0.6;
}

li:hover {
  cursor: pointer;
  color: rgba(231,100,83,1);
}

.header{
    display: block;
    position: relative;
}

.nav-item-icon-left :hover {
    color: rgba(231,100,83,1);
}

.nav-link:hover {
    color: rgba(231,100,83,1);  
}

.focus-item{
    color: rgba(231,100,83,1);
}

.nav-item-right :hover{
    color: rgba(231,100,83,1);
}

</style>
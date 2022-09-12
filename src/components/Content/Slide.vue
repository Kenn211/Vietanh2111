<script setup lang="ts">

</script>

<template>
    <div class="container-fluid px-0">
        <div id="carouselExampleIndicators" class="carousel slide slide-show" data-bs-ride="carousel">
            <div class="carousel-indicators">
                <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
                <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="1" aria-label="Slide 2"></button>
                <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="2" aria-label="Slide 3"></button>
            </div>
            <div class="carousel-inner">
                <div class="carousel-item active">
                    <img src="../../assets/sample-1.jpg" class="d-block w-100" alt="...">
                    <span class="title"><span>aaa</span></span>
                </div>
                <div class="carousel-item">
                    <img src="../../assets/sample-2.jpg" class="d-block w-100" alt="...">
                </div>
                <div class="carousel-item">
                    <img src="../../assets/sample-3.jpg" class="d-block w-100" alt="...">
                </div>
            </div>
            <button class="carousel-control-prev slide-button" type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide="prev">
                <span>
                    <i class="fas fa-arrow-circle-left"></i>
                </span>
                <span class="visually-hidden">Previous</span>
            </button>
            <button class="carousel-control-next slide-button" type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide="next">
                <span>
                    <i class="fas fa-arrow-circle-right"></i>
                </span>
                <span class="visually-hidden">Next</span>
            </button>
        </div>
    </div>
</template>

<style scoped>
    img {
        width: 100%;
        height: auto;
    }

    .slide-button{
        top: 0;
        font-size: 26px;
        width: 5%;
    }

    @keyframes iconAnimation {
        0%{
            margin-right: 270px;
        }
        100%{
            margin-right: 150px;
        }
    }

    @keyframes iconAnimation2 {
        0%{
            margin-left: 270px;
        }
        100%{
            margin-left: 150px;
        }
    }
    .title{
        position: absolute;
        z-index: 9;
        left: 9.5%;
        top: 8%;
    }
</style>
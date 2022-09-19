<sctipt setup lang="ts">
import HeaderCart from './HeaderCart.vue';
</sctipt>

<template>
    <div class="col d-flex justify-content-between">
        <div>
            <ul class="nav">
                <li class="nav-item">
                    <a class="nav-link1" href="#">Blog</a>
                </li>
                <li class="nav-item ">
                    <a class="nav-link1" href="#">Shop</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link1" href="#">Single Product Homepage Example</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link1" href="#">Prixing Tables</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link1" href="#">Review</a>
                </li>
            </ul>
        </div>

    </div>
</template>

<style scoped>
    .nav-item {
        padding: 30px 30px 20px 0px;
    }

    .nav-item .nav-link1{
        color: #d5d9db;
    }

    .nav-link1:hover {
        color: #fff;
    }
</style>
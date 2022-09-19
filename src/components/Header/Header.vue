<script setup lang="ts">
import HeaderTop from './HeaderTop.vue';
import HeaderBottom from './HeaderBottom.vue';

</script>

<template>
    <div class="header">
        <div class="container">
            <div class="row px-5 mx-5 d-flex flex-column">
                <HeaderTop></HeaderTop>
                <HeaderBottom></HeaderBottom>
            </div>
        </div>
    </div>
</template>

<style scoped>
    .header {
        background-color: #1d1e24;
        width: 100%;
        height: auto;
        padding-top: 42px;
    }



</style>
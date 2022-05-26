<script setup>
import Header from "../components/Header.vue"
</script>

<style scoped>
.img-home{
    width: 1400px;
}
@media only screen and (max-width: 768px) {
    main{
        /* margin-top: 40px; */
    }
    .img-home{
        width: 400px;
    }
}
</style>

<template>
    <div class="">
        <header>
            <Header />
        </header>
        <main class="">
            <div class="m-auto">
                <img src="../assets/img/homepage.png" class="w-full" />
            </div>
        </main>
    </div>
</template>
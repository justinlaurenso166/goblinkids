<script setup>
import Header from "../components/Header.vue"
</script>

<style scoped>
.img-home{
    width: 1400px;
}
.a{
    /* background: url("../assets/img/homepage.png") no-repeat center center fixed;
    height: 100vh;
     -webkit-background-size: cover;
  -moz-background-size: cover;
  -o-background-size: cover;
  background-size: cover; */
}
@media only screen and (max-width: 768px) {
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
        <main class="a">
            <div class="pt-2 m-auto xl:-mt-14">
                <!-- <img src="../assets/img/homepage.png" class="w-full" /> -->
            </div>
        </main>
    </div>
</template>
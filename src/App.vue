<script setup>
</script>

<template>
  <router-view></router-view>
  <div
    class="
      bg-white
      fixed
      bottom-14
      right-0
      left-0
      2xl:w-1/2
      w-5/6
      m-auto
      shadow-lg shadow-gray-400
      lg:px-7
      py-4
      rounded-lg
      px-4
    "
  >
    <div class="flex lg:pr-10">
      <div class="flex-1 flex text-black items-center">
        <!-- <img src="./assets/img/Logo/5.png" class="lg:w-48 w-32"> -->
        <p
          class="
            tracking-wider
            uppercase
            font-bold
            lg:text-xl
            text-lg
            py-5
            lg:ml-10
          "
        >
          MINT YOUR GOBLIN KIDS!
        </p>
      </div>
      <div class="flex-1 flex justify-end self-center">
        <a target="_blank" href="">
          <button
            class="
              bg-prime
              font-bold
              tracking-widest
              text-white
              lg:py-4 lg:px-7
              text-xl
              px-3
              py-3
              rounded-lg
              lg:text-2xl lg:mr-0
              hover:bg-opacity-70
            "
          >
            MINT
          </button>
        </a>
      </div>
    </div>
  </div>
</template>

<style>
#app {
  font-family: "Montserrat", sans-serif;
  background-color: #1A1B1D;
  height: 100vh;
  overflow-y: auto;
  overflow-x: hidden;
}
</style>

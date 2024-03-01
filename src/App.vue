<script setup>
import HeaderCalcVue from "./components/HeaderCalc.vue";
import Display from "./components/Display.vue";
import Keyboard from "./components/Keyboard.vue";
</script>

<template>
  <div class="calculadora">
    <HeaderCalcVue/>
    <Display/>
    <Keyboard />    
  </div>
</template>

<style scoped>
.calculadora {
  height: 580px;
  width: 380px;
  background-color: #3E4B5B;
}

</style>

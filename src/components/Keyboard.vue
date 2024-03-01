

<template>
  <div class="keyboard">
    <button class="row-1">AC</button>
    <button class="row-1">+/-</button>
    <button class="row-1">%</button>
    <button class="row-1">÷</button>
    <button @click="insert">7</button>
    <button @click="insert">8</button>
    <button @click="insert">9</button>
    <button>x</button>
    <button @click="insert">4</button>
    <button @click="insert">5</button>
    <button @click="insert">6</button>
    <button>-</button>
    <button @click="insert">1</button>
    <button @click="insert">2</button>
    <button @click="insert">3</button>
    <button>+</button>
    <button class="btn-zero">0</button>
    <button>.</button>
    <button class="btn-equal">=</button>
  </div>
</template>

<script>
export default {
  name: "Keyboard",
  methods: {
    insert() {
      console.log("Clicou no kayboard");
    },
  },
};
</script>

<style scoped>
.keyboard {
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  flex: 1;
}
.keyboard button {
  background-color: #3e4b5b;
  color: #fff;
  font-size: 30px;
  border: 0.1px solid #ffffff21;
  border-top: none;
  border-right: none;
  cursor: pointer;
  min-height: 80px;
  max-width: 100%;
  transition: background-color 0.2s;
}
.keyboard button:active {
  background-color: rgba(255, 255, 255, 0.1);
}

.keyboard .row-1 {
  color: #ffffffab;
}

.keyboard .btn-zero {
  grid-column: 1 / span 2;
  text-align: left;
  padding-left: 30px;
}
.keyboard .btn-equal {
  background-color: #feb23b;
}
</style>

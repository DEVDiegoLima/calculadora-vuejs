<script>
export default {
  name: "HeaderCalc",
};
</script>

<template>
  <div class="calc-container">
    <span>{{ calc }}</span>
  </div>
</template>

<style scoped>
.calc-container {
  height: 60px;
  width: 100%;
  background-color: #475568;
  display: flex;
  align-items: center;
  justify-content: flex-end;
  padding-right: 30px;
}

.calc-container span {
  color: #848b96;
  font-size: 20px;
}
</style>

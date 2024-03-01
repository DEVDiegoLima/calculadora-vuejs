<script>
export default {
  name: "Display",
};
</script>

<template>
  <div class="display">
    <span>357</span>
  </div>
</template>

<style scoped>
.display {
  margin-top: 5px;
  height: 120px;
  width: 100%;
  background-color: #475568;
  display: flex;
  justify-content: flex-end;
  align-items: center;
  padding-right: 30px;
}

.display span {
  color: #fff;
  font-size: 60px;
  font-weight: 100;
}
</style>

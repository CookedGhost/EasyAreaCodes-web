<script setup lang="ts">

</script>

<template>
  <div class="btn-wrapper">
    <el-row class="mb-4">
      <el-button id="add-error" type="primary" size="large">添加勘误</el-button>
    </el-row>
  </div>
</template>

<style scoped>
.main-wrapper {
  width: 800px;
  min-width: 200px;
}

#input {
  resize: none;
  position: relative;
  display: block;
  width: 100%;
  padding: 10px 11px;
  border: none;
  outline: none;
  box-sizing: border-box;
  border-radius: 5px;
  box-shadow: 0 0 0 1px rgb(163, 163, 163) inset;
  margin-bottom: 20px;
  font-family: Arial, Helvetica, sans-serif;
}

.btn-wrapper {
  width: 100%;
  padding-top: 15px;
}
@media screen and (max-width: 960px) {
  .main-wrapper {
    width: 100%;
  }
}
#add-error {
  margin: auto;
}
</style>
<template>
  <div class="common-layout">
    <el-container>
      <el-main>
        <el-tabs type="border-card" stretch="true">
          <el-tab-pane label="地区查询" name="list">
            <el-input
                v-model="textarea"
                :rows="5"
                type="textarea"
                placeholder="请输入你要查询的区位码/地区"
            />
          </el-tab-pane>

          <el-tab-pane label="地区总览" name="map">

          </el-tab-pane>>
        </el-tabs>
      </el-main>
    </el-container>
  </div>
</template>

<script lang="ts" setup>
import {ref} from 'vue'
const textarea = ref('')
</script>

<style>
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


</style>
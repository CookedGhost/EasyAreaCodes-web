<template>
  <div class="wrapper">
    <div class="main-wrapper">
      <Title />
      <Main />
      <AddErrors />
    </div>
  </div>
</template>

<script>
import Title from "./components/Title.vue";
import Main from "./components/Main.vue";
import AddErrors from "@/components/AddErrors.vue";

export default {
  name: 'App',
  components: {
    AddErrors,
    Title,
    Main
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
.wrapper {
  width: 100%;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}
body::-webkit-scrollbar {
  display: none;
}
body {
  background-color: rgb(242, 242, 242);
}
</style>

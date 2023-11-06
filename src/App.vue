<script setup lang="ts">
import TodoList from './components/TodoList.vue';


</script>

<template>
  <header>
    <img alt="Vue logo" class="logo" src="@/assets/logo.svg" />
  </header>
  <TodoList></TodoList>

</template>

<style >

* {
  box-sizing: border-box;
}

.container {
  max-width: 600px;
  margin: 0 auto;
}


#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  margin-top: 60px;
  font-size: 24px;
}

.logo {
  display: block;
  margin: 20px auto;
  height: 75px;
}

</style>

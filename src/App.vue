<template>
  <div id="app" class="container">
    <img src="./assets/logo-ts.png" class="logo">
    <todo-list> </todo-list>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld'
import TodoList from './components/TodoList'

export default {
  name: 'App',
  components: {
    HelloWorld,
    TodoList,
  }
}
</script>

<style>

* {
  box-sizing: border-box;
  background-color: turquoise;
}

.container {
  max-width: 50%;
  margin: 0 auto;
}

#app { 
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: black;
  margin-top: 60px;
  font-size: 17px;
}
.logo {
  display: block;
  margin: 20px auto;
  height: 20%;
  width: 20%;
}
</style>

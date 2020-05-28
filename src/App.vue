<template>
  <div id="app">
    <ToDo v-bind:todos="todos" />
  </div>
</template>

<script>

import ToDo from './components/Todos';

export default {
  name: 'App',
  components: {
    ToDo
  },

  data() {
    return {
        todos: [
          {
            id: 1,
            title: "Eat",
            completed: false
          },
          {
            id: 2,
            title: "Drink",
            completed: false
          },
          {
            id: 3,
            title: "Code",
            completed: false
          },
          {
            id: 4,
            title: "Sleep",
            completed: false
          }
        ]
    }
  }
}
</script>

<style>
  *{
    box-sizing: border-box;
    margin: 0;
    padding: 0;
  }
  body{
    font-family: Arial, Helvetica, sans-serif;
    line-height: 1.4;
    background-color: rgb(245, 245, 245);
    color: black;
  }
</style>

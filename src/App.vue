<template>
  <div>
    <h1>{{name}}</h1>
    <h2 :title="name">test</h2>
    <Todo />
  </div>
</template>

<script>
import Todo from './components/TodoList'
export default {
  data() {
      return {
        name: "Sandip"
      };
  },
  components: {
    // Add a reference to the TodoList component in the components property
    Todo
  }
}
</script>

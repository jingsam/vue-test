<template>
  <div>
    <ul>
        <li v-for="todo in todos">
            {{ todo.text }}
        </li>
    </ul>
  </div>
</template>

<style>
  
</style>

<script>
export default {
  data () {
    return {
      todos: [
        {text: "A"},
        {text: "B"},
        {text: "C"}
      ]
    }
  }
}
</script>

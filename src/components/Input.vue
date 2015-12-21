<template>
  <div>
    <p>{{ message }}</p>
    <input type="text" v-model="message">
  </div>
</template>

<style>
  
</style>

<script>
export default {
  data () {
    return {
      message: 'hello, vuejs!'
    }
  }
}
</script>

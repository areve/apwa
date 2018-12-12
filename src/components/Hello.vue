<template>
  <div class="hello">
    <h1>PWA</h1>
    <p>{{counter}}</p>
    <button @click="bump">Bump</button>
  </div>
</template>

<script>
export default {
  name: 'hello',
  data () {
    return {
      counter: 1
    }
  },
  methods: {
    bump () {
      this.counter++
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>
</style>

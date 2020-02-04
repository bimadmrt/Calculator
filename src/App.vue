<template>
  <div id="app">
    <h1>／人◕ ‿‿ ◕人＼</h1>
    <h1>بِسْمِ اللَّهِ الرَّحْمَنِ الرَّحِيمِ</h1>
    <Calculator />
    <h1>الْحَمْدُ لِلَّهِ رَبِّ الْعَالَمِينَ</h1>
  </div>
</template>

<script>
import Calculator from './components/Calculator.vue'

export default {
  name: 'app',
  components: {
    Calculator
  },
  data () {
    return ({
      message: null
    })
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>

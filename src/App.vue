<template>
  <section>
    <h3>{{userName}}</h3>
  </section>
</template>

<script>
export default {
  name: 'App',
  data(){ return{userName:"Mark Ho"}}
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
</style>

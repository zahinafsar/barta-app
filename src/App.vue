<template>
  <div id="body">
      <Bar/>
      <Nav/>
      <router-view/>
  </div>
</template>

<script>
import Nav from './components/nav'
import Bar from './components/bar'

export default {
  name: 'App',

  components: {
    Nav,
    Bar
  },

  data: () => ({
    //
  })
}
</script>

<style scoped lang="css">
#body{
  margin: auto;
  max-width: 500px;
  background-color: white;
  max-height: 100%;
  min-height: 100vh;
}
</style>

<style scoped lang="scss">
</style>

<style lang="css">
body{
  background-color: #633799;
}
*{
  font-family: monospace;
}
</style>

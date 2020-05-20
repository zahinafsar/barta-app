<template>
<v-app-bar>
<img height="150px" src="../assets/img/barta.svg"/>
<v-toolbar-title>Barta</v-toolbar-title>
</v-app-bar>
</template>

<script>
export default {
  name: 'Bar'
}
</script>
<style scoped lang="css">
.v-app-bar {
  color: black;
  position: fixed;
  max-width: 500px;
  margin: auto;
  z-index: 9999999
}
.theme--light.v-app-bar.v-toolbar.v-sheet {
  background-color: white
}
</style>

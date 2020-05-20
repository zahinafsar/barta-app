<template>
  <v-bottom-navigation
    :value="activeBtn"
    grow
    color="pink"
  >
    <router-link to='/profile'>
      <v-btn>
        <span>Profile</span>
        <v-icon>mdi-heart</v-icon>
      </v-btn>
    </router-link>

    <router-link to='/'>
      <v-btn>
        <span>Home</span>
        <v-icon>mdi-history</v-icon>
      </v-btn>
    </router-link>

    <router-link to='/store'>
      <v-btn>
        <span>Store</span>
        <v-icon>mdi-map-marker</v-icon>
      </v-btn>
    </router-link>

  </v-bottom-navigation>
</template>

<script>
export default {
  name: 'Nav',
  props: {
    msg: String
  },
  data () {
    return {
      activeBtn: 1
    }
  }
}
</script>

<style scoped lang="css">
.v-item-group.v-bottom-navigation{
  position: fixed;
  left: auto;
  max-width: 500px
}
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
  margin: auto;
}
</style>

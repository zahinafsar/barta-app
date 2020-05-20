<template>
  <div class="home">
   <Post/>
   <button>see more</button>
  </div>
</template>

<script>
import Post from '../components/post'

export default {
  name: 'App',
  components: {
    Post
  },
  data: () => ({
  })
}
</script>
<style scoped lang="css">
button{
  position: absolute;
  bottom: 70px;
  background-color: #e1295d;
  padding: 10px;
  border-radius: 0px 50px 50px 0px;
  color: white
}
button:hover{
  padding-left: 50px;
  transition: .5s
}
</style>

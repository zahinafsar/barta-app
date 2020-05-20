<template>
  <div class="body-post">
    <div class="space"></div>

  <div class="post-body">
    <div class="post">sdfgscvsdf dfsdfv sdfvf ,vb dfvbvb cfb vb gvbxcvbfvb xfbfxbxvvhdfv dfv dfvb jdfb kbfxv xfkdgvdfhbvdfy bvgfvhdfb vydfvh bdfyugv hfygfy dfyugvy dfbgyudf vbdfkygyd gdfyg ydfgydfgy dfgyusdfy bsdfygy cvydyfgyshd yyfhggy hdfyghu dhfyg hfugh fughfhguih dfuig hduighdfuig
    </div>
    <div class="like-comment">
    <div class="like">
        <v-icon>mdi-history</v-icon>
    </div>
    <input type="text" class="comment"/>
    </div>
  </div>
  <div class="post-body">
    <div class="post">sdfgscvsdf dfsdfv
    </div>
    <div class="like-comment">
    <div class="like">
        <v-icon>mdi-history</v-icon>
    </div>
    <input type="text" class="comment"/>
    </div>
  </div>

  </div>
</template>

<script>
// import axios from 'axios'

export default {
  name: 'Post',
  data: () => ({
    postdata: ''
  }),
  computed: {
    // axiosData: function () {
    //   axios
    //     .get('https://jsonplaceholder.typicode.com/posts')
    //     .then(function (r) {
    //       this.postdata = r.data
    //       console.log(this.postdata)
    //     })
    // }
  }
}
</script>

<style scoped lang="css">
.space{
  height: 60px;
}
.post-body{
  padding: 10px;
  background-color: #b2dbdd;
  width: 95%;
  margin: 15px auto;
  border-radius: 5px;
}
.post{
  padding:10px;
  background-color: white;
  width: 100%;
  margin-bottom: 10px;
  min-height: 90px;
  border-radius: 5px;
}
.like-comment{
  display: flex;
  flex-direction: row;
  justify-content: space-between;
}
.like{
  margin: auto;
}
.comment{
  background-color: white;
  width: 90%;
  border:none;
  padding-left: 20px;
  padding: 5px;
  border-radius: 5px;
}
</style>

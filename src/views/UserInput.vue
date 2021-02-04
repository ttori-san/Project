<template>
  <div id="UserInput">
  <Header />
    <form class="form" method="post">
      <div class="flex">
        <input placeholder="date" />
      </div>
      <div class="flex">
        <input placeholder="species" />
      </div>
      <div class="flex">
        <input placeholder="place" />
      </div>
      <div class="flex">
        <textarea placeholder="comments" />
      </div>
      <div class="flex" v-on="submit">
        <button>鳥信を送る</button>
      </div>
    </form>
  </div>
</template>

<script>
import Header from '../components/Header.vue'
export default {
  components: { 
    Header 
  },
  
}
</script>

<style scoped>
#UserInput{
  color:white;
  border:cadetblue
}
.flex{
  display: flex;
}
input,
textarea{
  width:80%;
  height:40px;
  margin:0 auto;
  margin-top:3%;
}
.submit{
  width:100px;
  height:32px;
  margin:0 auto;
  margin-top: 3%;
  background: rgb(12, 11, 11) none;
}
</style>
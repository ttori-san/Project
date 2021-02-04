<template>
  <div class="home">
    <div v-for="(value,index) in info" :key="index">
      <div class="flex">
        <p class="date">{{value.date}} , {{value.species}} ,{{value.place}}</p>
      </div>
      <div class="flex">
        <p class="comments">{{value.comments}}</p>
      </div>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
export default {
  name: 'Home',
  components: {
  },
  data(){
    return{
      info:[{date:"2021年2月4日", species:"メジロ", place:"福岡市早良区室見川",comments:"梅の木に留まっていた",}]
    }
  }
}
</script>
<style scoped>
.flex{
  display:flex
}
.comments{
  margin:5px 10px;
}
</style>

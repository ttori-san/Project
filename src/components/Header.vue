<template>
  <div id="header">
    <div class="header-logo">
      <p>鳥信掲示板</p>
    </div>
    <div class="header-button">
      <span>
      <a>home</a>
        </span>
      <span>
       <a>新規会員登録</a>
      </span>
    </div>
  </div>
</template>
<script>
export default {
  
}
</script>
<style scoped>
#header{
  display: flex;
}
.header-logo{
  font-size: 24px;
  font-family:'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  margin:0 auto;
  padding-left:19%;
}
.header-button span{
  text-align: justify;
  padding:30px;
}
</style>
<script>
export default { 
  data(){
    return{
      message:'La mia prima app con Vite!'
    }
  }
}
</script>

<template>

  <div class="text">
    <h1>{{ message }}</h1>
  </div>

</template>

<style scoped>
.text{
  color: red;
  background-color: gold;
  border-radius: 20px ;
  padding: 20px;
}
</style>

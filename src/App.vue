<template>
 <div class="container">
   <todos></todos>
 </div>
</template>

<script>
import Todos from './components/ToDos.vue'
export default {
  name: 'App',
  components: {
    Todos
  }
}
</script>

<style>
body{
  font-family: "Franklin Gothic Medium", "Arial Narrow", Arial, sans-serif;
  line-height:1.6s;
  background: #e8f7f0;
}
.container{
  max-width:1100px;
  margin:auto;
  overflow:auto;
  padding:0 2rem;
}
</style>

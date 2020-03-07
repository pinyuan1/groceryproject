<template>
    <div>
        <button v-on:click="counter = counter + 1"> +</button>
        <a>{{ counter }}</a>
        <button v-on:click="counter = counter - 1"> -</button>
    </div>
</template>

<script>
export default {
  data(){
    return{
        counter:0
        }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped> 
 a{
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  text-align: center; 
  color: black; }
</style>
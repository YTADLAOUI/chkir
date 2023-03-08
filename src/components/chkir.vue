<template>
<div>
  <h1>hello {{name}}</h1>
  <button @click="$emit('mohamed')">click me</button>
</div>
  
</template>

<script>
export default {
data() {
  return {
    name: "chkir"
  }
},
methods: {
  changeName(){
    this.name="tadlaoui"
  }
},
props :{
  name
}
}
</script>

<style>

</style>
<template>
<div>
  <h1>hello {{name}}</h1>
  <button @click="$emit('smiya','this is mada fucker')">click</button>
</div>
  
  
</template>

<script>
export default {
props :{
  name:String
}
}
</script>

<style>

</style>
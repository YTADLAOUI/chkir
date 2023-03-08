<template>
<header>
    <hello 
    @mohamed='changeTitle'
    :name='titel'/>
    <tadlaoui v-show="show" @smiya='changeSmiya' name="mustapha"></tadlaoui>
</header>
  
</template>

<script>
import hello from './components/chkir.vue'
import tadlaoui from './components/tadlaoui.vue'
export default {
components :
{
  hello,
  tadlaoui

},
data() {
  return {
    titel: "mohamed",
    show: true
  }
},
methods: {
  changeTitle(){
    this.titel="tadlaoui"
    this.show=!this.show
  },
  changeSmiya(data){
    console.log(data)
  }
},

}
</script>

<style>

</style>

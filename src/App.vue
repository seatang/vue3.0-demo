<template>
  <div>
      <h1>{{title}}</h1>
      <h2>{{ count }}</h2>
      <input type="text" v-model="count">
      <br>
      <button>add</button>
  </div>
</template>

<script>
import { defineComponent} from 'vue'
export default defineComponent({
    setup(){
        return{
            title:'vue3.0',
            count:1
        }
    }
})
</script>

<style>
div{
    color: red;
}
</style>
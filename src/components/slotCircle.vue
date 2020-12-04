<template>
  <div>
    你叫什么啊?
    <slot name='header' :whatname='name'></slot>
    <slot name='body' :cityname='list'></slot>
  </div>
</template>

<script>
export default {
  data(){
    return {
      list:['北京','上海','天津'],
      name:'hello world'
    }
  }
}
</script>

<style>

</style>
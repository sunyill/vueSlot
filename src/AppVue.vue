<template>
  <div>
    <!-- <vue-name >
      <p slot="up">我是前插槽</p>
      <button slot="down">我是吼吼</button>


    </vue-name>

    <vue-name>
     <slot></slot>
    </vue-name>

    <vue-name>
      我爱什么啊
    </vue-name> -->
    <vue-little>
      <div slot="small">你能把我怎么样</div>
      <div slot="big"> 我能一口把你吃掉</div>
    </vue-little>
  </div>
</template>

<script>
// import vueName from '@/components/slot-name.vue'
import vueLittle from '@/components/slot-little.vue'
// import SlotReserve from './components/slot-reserve.vue'
// import SlotReserve from './components/slot-reserve.vue'
export default {
  components:{
    // vueName,
    vueLittle
    // SlotReserve
   
  }
}
</script>

<style>

</style>
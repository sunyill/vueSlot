<template>
  <div id="app">
    <slot-test> 
      <p>踏遍万千山河,数尽满天繁星,无一是你,无一不是你</p>
    </slot-test>

    <slot-reserve>
      <button>确认</button>
    </slot-reserve>
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import slotTest from '@/components/slot.vue'
import slotReserve from '@/components/slot-reserve.vue'

export default {
  name: 'App',
  components: {
    // HelloWorld
    slotTest,
    slotReserve
  }
}
</script>

<style>
p{
  font-size: 20px;
  color: blueviolet;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>

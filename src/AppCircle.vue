<template>
  <div>
    <slot-circle >
      <span slot='header' slot-scope="obj">{{obj.whatname}}</span>
      <div slot="body" slot-scope='object'>
       <div v-for="(item,index) in object.cityname" :key="index">{{item}}</div> 
      </div>
    </slot-circle>
  </div>
</template>

<script>

import SlotCircle from './components/slotCircle.vue'
export default {
  components:{
    SlotCircle
  },
  data(){
    return {
      name:'wangzhan'
    }
  }
}
</script>

<style>

</style>
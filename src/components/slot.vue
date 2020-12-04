<template>
  <div>this is slot test
    <slot/>
    <!-- <div v-for="(item,index) in list" :key="index">
      {{item}}
    </div> -->
    <!-- <div v-for="(item,index) in list" :key="index">
       <img :src="item">
    </div> -->
   
   
  </div>
</template>

<script>
export default {
  data(){
    return {
     list:['http://cms-bucket.ws.126.net/2020/1203/98700a43j00qkqnbh004mc000ak0057c.jpg?imageView&thumbnail=453y225&quality=85',
     'http://cms-bucket.ws.126.net/2020/1203/6fd46a41j00qkqkqk0057c000fa007lc.jpg?imageView&thumbnail=453y225&quality=85'
     ]
    }
  }
}
</script>

<style>

</style>
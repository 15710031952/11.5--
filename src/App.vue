<!--  -->
<template>
    <div>
      
    </div>
</template>

<script>
export default {
  data () {
    return {
      arr:['a',2,4,'5g','h']
    };
  },
  created(){
    shijian(){
      arr.forEach(item=>{
        console.log(item)
      })
    }
  }
}

</script>
<style lang='scss' scoped>

</style>
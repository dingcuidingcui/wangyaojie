<template>
    <div class="error top">
      <HeaderTop title="网页走丢了。。。"/>>
    
      <img src="./timg.jpg" alt="">
    </div>
</template>

<script>
 import HeaderTop from '../../components/HeaderTop/HeaderTop.vue'
    export default {
        name: "Error",
      components: {HeaderTop}
    }
</script>

<style scoped lang="scss">
.error{
  text-align: center;
  img{
    display: inline-block;
    width: 100%;
  }
}
</style>

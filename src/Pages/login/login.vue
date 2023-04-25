<template>
  <div class="login">

  </div>
</template>

<script>
export default {
  methods: {
    login() {
      this.$router.push('/index')
    }
  }
}


</script>

<style lang="less" scoped>
.login {
  width: 100%;
  height: 100%;
  overflow: hidden;
  background-image: url('https://gimg2.baidu.com/image_search/src=http%3A%2F%2Fpic1.win4000.com%2Fwallpaper%2F2018-01-08%2F5a52d7086f955.jpg&refer=http%3A%2F%2Fpic1.win4000.com&app=2002&size=f9999,10000&q=a80&n=0&g=0n&fmt=auto?sec=1673712252&t=bc7d223d6cfe76b73c54cef92553690c');
  background-size: 100% 100%;
  position: relative;


}
</style>
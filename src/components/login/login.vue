<template>
  <div id="app">
  <h2>购物车</h2>
    <form>
      <div>
        <label>用户名</label>
        <p><input placeholder="请输入用户名..." v-model="name"/></p>
      </div>
      <div>
        <label>密码</label>
        <p><input v-model="pwd" type="password" placeholder="请输入密码..."/></p>
      </div>
      <br/>
      <button @click="isLogin">登陆</button>
    </form>
  </div>
</template>

<script type="text/ecmascript-6">
  export default{};
</script>

<style lang="stylus" rel="stylesheet/stylus">

</style>

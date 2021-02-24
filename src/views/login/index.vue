<template>
  <div class="login-container">
    <van-nav-bar title="登录" />
    <van-form>
      <van-field name="用户名" placeholder="用户名" />
      <van-field type="password" name="密码" placeholder="密码" />
      <div style="margin: 16px;">
        <van-button block type="info" native-type="submit">
          提交
        </van-button>
      </div>123
    </van-form>
  </div>
</template>

<script>
export default {
  name: 'LoginPage'
}
</script>
<style scoped lang="less"></style>

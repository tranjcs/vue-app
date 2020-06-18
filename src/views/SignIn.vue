<template>
  <div class="signin view">
    <h2>SIGN IN</h2>
    <form>
      <div class="row">
        <input type="text" id="email" name="email" placeholder="Email" />
      </div>

      <div class="row">
        <input type="text" id="password" name="password" placeholder="Password" />
      </div>
      <div class="row">
        <button class="input">Sign In</button>
      </div>
    </form>
  </div>
</template>

<script>
export default {
  name: "signin"
};
</script>
<style lang="scss">
.signin {
}
</style>


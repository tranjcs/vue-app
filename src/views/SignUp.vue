<template>
  <div class="signup view">
    <h2>SIGN UP</h2>
    <form>
      <div class="row">
        <input type="text" id="email" name="email" placeholder="Email" />
      </div>

      <div class="row">
        <input type="text" id="password" name="password" placeholder="Password" />
      </div>
      <div class="row">
        <button class="input">Sign Up</button>
      </div>
    </form>
  </div>
</template>

<script>
export default {
  name: "signup"
};
</script>
<style lang="scss">
.signup {
}
</style>


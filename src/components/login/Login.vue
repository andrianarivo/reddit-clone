<template>
  <div>
    <img class="art" :src="require('@/assets/reddit__login_art.png')" />
    <section class="section login__section">
      <div class="login__head">
        <p class="title is-5">Login</p>
        <p class="subtitle is-6">
          By continuing, you agree to our
          <a href="https://www.redditinc.com/policies/user-agreement"
            >User Agreement</a
          >
          and
          <a href="https://www.redditinc.com/policies/privacy-policy"
            >Privacy Policy</a
          >.
        </p>
      </div>
      <FormLogin class="mt-6" />
    </section>
  </div>
</template>

<script>
import FormLogin from "./FormLogin.vue";

export default {
  name: "Login",
  components: {
    FormLogin,
  },
};
</script>

<style scoped>
.art {
  float: left;
  object-fit: cover;
  height: 100vh;
  width: 11vw;
}
.login__section {
  display: block;
  position: absolute;
  top: 0;
  left: 11vw;
}
</style>

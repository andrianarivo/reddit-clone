<template>
  <div class="columns">
    <div class="column is-7">
      <!-- AUTH LOGIN -->
      <button class="button is-normal is-fullwidth is-link is-outlined">
        <span class="icon">
          <i class="fab fa-google"></i>
        </span>
        <span class="is-uppercase  is-size-7 has-text-weight-semibold"
          >continue with google</span
        >
      </button>
      <button class="button is-normal is-fullwidth is-link is-outlined mt-1">
        <span class="icon">
          <i class="fab fa-apple"></i>
        </span>
        <span class="is-uppercase is-size-7 has-text-weight-semibold"
          >continue with apple</span
        >
      </button>
      <!-- AUTH LOGIN -->

      <div class="flex__or__divider my-5">
        <hr class="hr" />
        <span
          class="is-uppercase has-text-grey has-text-weight-semibold"
          >or</span
        >
        <hr class="hr" />
      </div>

      <!-- LOGIN NORMALE -->
      <div class="field">
        <div class="control">
          <input class="input" type="text" placeholder="Username" />
        </div>
      </div>

      <div class="field">
        <div class="control">
          <input class="input" type="password" placeholder="Password" />
        </div>
      </div>

      <div class="control">
        <button
          class="button is-size-7 is-link is-uppercase has-text-weight-semibold is-fullwidth"
        >
          Log In
        </button>
      </div>

      <p>Forgot your <a>username</a> or <a>password</a> ?</p>

      <p class="mt-5">
        New to Reddit?
        <a class="is-uppercase is-size-7 has-text-weight-semibold">sign up</a>
      </p>
      <!-- LOGIN NORMALE -->
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.flex__or__divider {
  display: flex;
  justify-content: space-between;
  align-items: center;
}
.hr {
  width: 100px;
}
</style>

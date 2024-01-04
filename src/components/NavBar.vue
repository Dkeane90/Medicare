<template>
  <div class="container-1">
    <div>
      <router-link to="/">
        <img src="../assets/m 1.png" alt="Medicare logo"
      /></router-link>
    </div>
    <div class="link-container">
      <router-link to="/">Home</router-link>
      <router-link to="/">Contact Us</router-link>
      <router-link class="Call" to="/">Call</router-link>
    </div>
  </div>
</template>

<script>
import Button from "./Button.vue";
</script>

<style lang="postcss" scoped>
.container-1 {
  @apply px-10 py-4 text-blue-700 font-semibold text-xl border-b-4
  border-blue-700 flex w-screen justify-between;
}

.Call {
  @apply bg-red-700 rounded text-white p-4;
}
.link-container {
  @apply flex gap-6 items-center;
}

router-link {
  @apply cursor-pointer;
}
</style>

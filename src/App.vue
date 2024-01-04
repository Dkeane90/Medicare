<script setup>
import HelloWorld from "./components/HelloWorld.vue";
import Button from "./components/Button.vue";
import BaseButton from "./components/BaseButton.vue";
import NavBar from "./components/NavBar.vue";
</script>

<template>
  <div class="main-div">
    <main>
      <section>
        <NavBar></NavBar>
      </section>
    </main>
  </div>
</template>

<style lang="postcss" scoped>
.main-div {
  @pply w-screen;
}
</style>

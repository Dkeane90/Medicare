<template>
  <div>
    <button class="Base-btn">
      <slot></slot>
    </button>
  </div>
</template>

<script></script>

<style lang="postcss" scoped>
.Base-btn {
  @apply bg-red-600 text-white font-bold px-8;
}
</style>

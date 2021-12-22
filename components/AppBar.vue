<template>
<div>
  <nav class="flex justify-between items-center py-2 px-10 fixed w-full bg-white shadow-lg">
    <div class="p-4 font-bold">Logo</div>
    <div>
      <NuxtLink to="/" class="btn">Index</NuxtLink>
      <NuxtLink to="/about" class="btn">About</NuxtLink>
      <NuxtLink to="/todos" class="btn">Todo</NuxtLink>
    </div>
  </nav>
</div>
</template>
<script>
export default {};
</script>

<style lang="scss" scoped>
.btn {
  @apply px-4 py-2 text-gray-500 rounded-lg hover:bg-green-100 hover:text-green-700;
  &.nuxt-link-exact-active {
    @apply bg-green-800 text-white;
  }
}
</style>
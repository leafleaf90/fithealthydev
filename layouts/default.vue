<template>
  <div>
    <!-- <nav class="text-white py-4 px-2">
      <NuxtLink to="/" class="link">Home</NuxtLink>

      <NuxtLink to="/blog" class="link">Blog</NuxtLink>
    </nav> -->

    <main>
      <div>
        <slot />
      </div>
    </main>
  </div>
</template>

<style>
.link {
  margin-right: 1rem;
}
</style>

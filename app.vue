<template>
  <NuxtLayout>
    <Particles></Particles>
    <NuxtPage />
  </NuxtLayout>
</template>
<style lang="postcss">
html,
body {
  @apply font-body h-full;
}
body {
  @apply bg-gradient-to-t from-yellow-600 to-yellow-400;
  background-image: url("/img/beer.png");
}
</style>

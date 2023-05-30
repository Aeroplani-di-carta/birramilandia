<script setup>
const message = ref("ciao");
</script>
<template>
  <form
    class="w-full bg-red-950 p-6 mt-12 flex flex-col text-white z-50 relative"
  >
    <fieldset class="grid grid-cols-12 gap-4">
      <label for="flex flex-col">
        <p>Nome</p>
        <input type="text"
      /></label>
      <label for="flex flex-col">
        <p>Email</p>
        <input type="email"
      /></label>
      <label for="flex flex-col">
        <p>Email</p>
        <input v-model="message" type="email"
      /></label>

      <button class="col-span-3 bg-white bg-opacity-20 py-2 px-12">
        Invia
      </button>
    </fieldset>
  </form>
</template>
<style lang="postcss">
input {
  @apply bg-transparent border-b border-red-900 w-full;
}
</style>

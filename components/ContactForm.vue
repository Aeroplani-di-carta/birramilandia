<template>
  <form
    class="w-full bg-red-950 p-6 mt-12 flex flex-col text-white z-50 relative"
  >
    <fieldset class="grid grid-cols-2 gap-4">
      <label for="flex flex-col">
        <p>Nome</p>
        <input type="text" class="bg-transparent border-b border-red-900"
      /></label>
      <label for="flex flex-col">
        <p>Email</p>
        <input type="email" class="bg-transparent border-b border-red-900"
      /></label>

      <label for="flex flex-col">
        <p>Messaggio</p>
        <textarea class="w-full h-full bg-transparent"></textarea>
      </label>
      <button class="col-span-full bg-white bg-opacity-20 py-2 px-12">
        Invia
      </button>
    </fieldset>
  </form>
</template>

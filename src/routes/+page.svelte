<script>
  import ContactCard from "./hero.svelte";
  import Feature from "./feature.svelte";
</script>

<nav class="container relative p-6 px-10 mx-auto">
  <div class="flex items-center justify-between">
    <!-- image -->
    <div class="pt-2">
      <img src="../src/image/logo.svg" alt="" />
    </div>
    <!-- menu -->
    <div class="hidden space-x-6 md:flex">
      <a href="#" class="hover:text-gray-400">about</a>
      <a href="#" class="hover:text-gray-400">product</a>
      <a href="#" class="hover:text-gray-400">about us</a>
      <a href="#" class="hover:text-gray-400">carers</a>
      <a href="#" class="hover:text-gray-400">coummunity</a>
    </div>
    <!-- button -->
    <a
      href="#"
      class="hidden p-3 px-6 pt-2 text-white bg-orange-600 rounded-full md:block baseline hover:bg-gray-400"
      >oke</a
    >
  </div>
</nav>

<ContactCard />
<Feature />

<style lang="postcss">
  :global(html) {
    background-color: theme(colors.gray.100);
  }
</style>

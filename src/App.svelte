<script>
  import Header from "./Pages/header/index.svelte"
</script>

<main class="flex h-screen w-screen bg-cover overflow-hidden">
  <Header />
</main>

<style global lang="postcss">
  @tailwind base;
  @tailwind components;
  @tailwind utilities;

  main {
    background: url(/assets/bg-blured.png) no-repeat bottom center;
  }
</style>

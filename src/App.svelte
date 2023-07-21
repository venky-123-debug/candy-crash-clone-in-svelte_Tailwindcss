<script>
  import Header from "./Pages/header/index.svelte"
</script>

<main class="h-screen w-screen bg-cover p-10 overflow-hidden">
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

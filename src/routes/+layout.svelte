<script>
  import Nav from "$lib/components/Nav.svelte";
  import "../app.css";
  import "@picocss/pico";

  let { children } = $props();
</script>

<main class="p-2 bg-neutral-200">
  <Nav />
  {@render children()}
</main>

<style>
  :global(html *) {
    line-height: 1.5;
    box-sizing: border-box;
  }
</style>

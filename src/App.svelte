<script>
  import Router from "svelte-spa-router";
  import Home from "./Home.svelte";
  import Add from "./Add.svelte";

  const routes = {
    "/": Home,
    "/add": Add,
    "*": Home,
  };
</script>

<main>
  <Router {routes} />
</main>

<style>
  main {
    background-color: rgb(255, 251, 246);
    padding: 2em;
    width: 100%;
    height: 100%;
    overflow-y: auto;
  }
</style>

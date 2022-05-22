<script>
  import Greeting from "./Greeting.svelte";
  import Card from "./Card.svelte";

  let name = "";
</script>

<main>
  <input placeholder="Enter your name" bind:value={name} />
  <div>Hello, {name}</div>
</main>

<style></style>

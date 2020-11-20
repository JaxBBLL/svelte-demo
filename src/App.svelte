<script>
  import HelloWorld from "./components/HelloWorld.svelte";
  let count = 0;
  function handleClick() {
    count++;
  }
  export let name;
</script>

<style>
</style>

<main>
  <h1>{name}</h1>
  <HelloWorld />
  <button type="button" on:click={handleClick}>clicked {count}</button>
</main>

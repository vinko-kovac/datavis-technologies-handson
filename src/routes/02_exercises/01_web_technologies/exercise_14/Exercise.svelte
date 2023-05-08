<script>
  let current = "";
</script>

<style>
  .curr {opacity : 0.5}
</style>

<!-- We will cover buttons later on! -->
<button class="btn btn-secondary" class:curr={current == "messi"} on:click={() => (current = "messi")}>
  Messi
</button>

<button class="btn btn-secondary" class:curr={current == "ronaldo"} on:click={() => (current = "ronaldo")}>
  Ronaldo
</button>

<button class="btn btn-secondary" class:curr={current == "neymar"} on:click={() => (current = "neymar")}>
  Neymar
</button>

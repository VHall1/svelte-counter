<script lang="ts">
  let count = 0;

  function handleClick() {
    count++;
  }
</script>

<main>
  <button on:click={handleClick}>Count is {count}</button>
</main>

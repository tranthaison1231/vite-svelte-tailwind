<script lang="ts">
  let count: number = 0;
  const increment = () => (count += 1);
</script>

<button on:click={increment} class="bg-red-900 mt-3 p-4 rounded-xl">
  Clicks: {count}
</button>

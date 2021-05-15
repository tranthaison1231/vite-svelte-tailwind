<script lang="ts">
  import Counter from './lib/Counter.svelte';
  import TailwindCss from './TailwindCSS.svelte';
</script>

<TailwindCss />
<main>
  <div class="rounded bg-red-900 p-6">
    <h1 class="m-2">Hello</h1>
  </div>
  <Counter />
</main>

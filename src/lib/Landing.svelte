<script lang="ts">
  import Counter from 'src/lib/Counter.svelte'
  import Logos from 'src/lib/Logos.svelte'
</script>

<div>
  <Logos />
  <h1>Vite + Svelte</h1>

  <div class="card">
    <Counter />
  </div>

  <p>
    Check out <a
      href="https://github.com/sveltejs/kit#readme"
      target="_blank"
      rel="noreferrer">SvelteKit</a
    >, the official Svelte app framework powered by Vite!
  </p>

  <p class="read-the-docs">Click on the Vite and Svelte logos to learn more</p>

  <a href="/not-found">Go to page that doesn't exist</a>
</div>

<style lang="postcss">
  h1 {
    @apply text-[3.2em] leading-[1.1em];
  }

  .card {
    @apply p-[2.5em];
  }

  .read-the-docs {
    @apply text-[#888] leading-9;
  }
</style>

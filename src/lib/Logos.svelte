<script lang="ts">
  import svelteLogo from 'src/assets/svelte.svg'
  import viteLogo from 'src/assets/vite.svg'
</script>

<div>
  <a href="https://vitejs.dev" target="_blank" rel="noreferrer">
    <img src={viteLogo} alt="Vite Logo" />
  </a>
  <a href="https://svelte.dev" target="_blank" rel="noreferrer">
    <img src={svelteLogo} alt="Svelte Logo" />
  </a>
</div>

<style lang="postcss">
  div {
    @apply flex justify-center;

    a {
      @apply first-of-type:hover:drop-shadow-[0_0_2em_#646cffaa];
      @apply last-of-type:hover:drop-shadow-[0_0_2em_#ff3e00aa];
      will-change: filter;
      transition: filter 300ms;

      img {
        @apply h-[10em] p-[2em];
      }
    }
  }
</style>

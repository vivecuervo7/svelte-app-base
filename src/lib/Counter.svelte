<script lang="ts">
  let count: number = 0
  const increment = () => {
    count += 1
  }
</script>

<button on:click={increment}>
  count is {count}
</button>

<style lang="postcss">
  button {
    @apply bg-[#f9f9f9] dark:bg-[#1a1a1a];
    @apply py-[0.6em] px-[1.2em] font-medium cursor-pointer;
    @apply rounded-[8px] border-[1px] border-transparent hover:border-[#646cff];
    transition: border-color 0.25s;

    &:focus,
    &:focus-visible {
      outline: 4px auto -webkit-focus-ring-color;
    }
  }
</style>

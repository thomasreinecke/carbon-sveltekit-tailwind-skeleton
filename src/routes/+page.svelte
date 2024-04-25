<script>
  import { Button } from 'carbon-components-svelte';
</script>

<div class="p-10 text-center bg-blue-200">
  <h1 class="text-3xl font-bold text-gray-800">Hello World</h1>
  <Button>Carbon Button</Button>
</div>

<style>
  :global(.bx--btn) {
    margin-top: 1rem;
  }
</style>

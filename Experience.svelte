<!-- Experience.svelte -->
<script>
  let isRed = false;

  function toggleColor() {
    isRed = !isRed;
  }
</script>

<div class="{isRed ? 'text-red-500' : ''}" on:click={toggleColor}>
  <!-- Your experience content here -->
</div>

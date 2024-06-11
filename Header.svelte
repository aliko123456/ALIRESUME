<!-- Header.svelte -->
<script>
  let isVisible = true;

  function toggleVisibility() {
    isVisible = !isVisible;
  }
</script>

{#if isVisible}
  <div on:dblclick={toggleVisibility}>
    <!-- Your header content here -->
  </div>
{/if}

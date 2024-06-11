<!-- Education.svelte -->
<script>
  let isMoved = false;

  function moveLeft() {
    isMoved = !isMoved;
  }
</script>

<div class="{isMoved ? 'translate-x-10' : ''}" on:click={moveLeft}>
  <!-- Your education content here -->
</div>

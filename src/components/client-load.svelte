<script>
  const js = 'client-load.svelte JS 8';
</script>

<div class="apple" style="border: 1px solid black;">
  <p>{js}</p>
  <p>client-load.svelte HTML 8</p>
  <p class="css"></p>
</div>

<style>
  .css:before {
    content: 'client-load.svelte CSS 8';
  }
</style>

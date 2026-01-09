<script>
  const js = 'client-only.svelte JS 2';
</script>

<div class="apple" style="border: 1px solid black;">
  <p>{js}</p>
  <p>client-only.svelte HTML 2</p>
  <p class="css"></p>
</div>

<style>
  .css:before {
    content: 'client-only.svelte CSS 2';
  }
</style>

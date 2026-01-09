<script>
  const js = 'ssr-only.svelte JS 1';
</script>

<div class="apple" style="border: 1px solid black;">
  <p>{js}</p>
  <p>ssr-only.svelte HTML 1</p>
  <p class="css"></p>
</div>

<style>
  .css:before {
    content: 'ssr-only.svelte CSS 1';
  }
</style>

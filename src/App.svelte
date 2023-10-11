<script>
  let active = false;
</script>

<span><input type='checkbox' bind:checked={active} />상태</span>

<p class:view={!active}>active is {active}</p>

<style>
  .view {
    display: none;
  }
</style>
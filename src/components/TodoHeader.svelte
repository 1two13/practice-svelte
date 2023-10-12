<script>
  export let todoValue
  export let handleTodoInputKeyup
</script>

<header>
  <div class='wrap'>
    <h1>Svelte Todo</h1>
    <input type='text' bind:value={todoValue} on:keyup={handleTodoInputKeyup}>
  </div>
</header>
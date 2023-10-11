<script>
  export let test = 0 // props

  function add() {
    test += 1;
  }
</script>

<button on:click={add}>ADD</button>
<script>
  import {getContext} from 'svelte'

  let handleIncrement = getContext('incrementCount')
  let count = getContext('count')
</script>
  
<button on:click={handleIncrement} >
  increment count [{count}]
</button>
<script>
import SubChild from './subChild.svelte'

export let handleValueAdd
export let carryValue
</script>
  
<SubChild {handleValueAdd} />
<p>전달된 값은 {carryValue}</p>
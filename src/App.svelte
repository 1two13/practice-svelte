<script>
import Child from './child.svelte'

let value = 0
let carryValue = 12

function handleValueAdd(event, param) {
  value += param
}
</script>

<p>value : {value}</p> 

<Child {handleValueAdd} {carryValue} />
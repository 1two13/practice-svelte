<script>
	let list = [
    {
      id: 0, 
      content: '밥먹기',
      done: true
    }, 
    {
      id: 1, 
      content: 'svelte 공부하기',
      done: false
    }
  ]
</script>

<ul>
  {#each list as item}
    <li>
      <p>{item.content}</p>
    </li>
  {/each}
</ul>
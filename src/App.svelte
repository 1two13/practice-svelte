<script>
  let todos = [
    {id: 0, content: '1번', done: false},
    {id: 1, content: '2번', done: true},
  ]
</script>

<ul>
  {#each todos as {id, content, done}, index}
    <li>
      <span>{index + 1}</span>,
      <span>{content}</span>,
      <span>{done}</span>
    </li>
  {/each}
</ul>
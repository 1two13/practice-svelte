<script>
  let selected = 0
</script>

<h2>size</h2>

<label>
  <input type='radio' bind:group={selected} value={1}>
  One Scoop
</label>

<label>
	<input type=radio bind:group={selected} value={2}>
	Two scoops
</label>

<p>선택된 라이도 버튼: {selected} 번째</p>
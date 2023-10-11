<script>
  let active
</script>

<input type='checkbox' bind:checked={active} /> boarder size 

<p class='box' class:checkBorder={active}>
  Style Box
</p>

<style>
	.box {
		padding: 10px;
		border: 1px solid #FF003A;
	}

	.checkBorder {
		border: 5px solid #FF003A;
	}
</style>
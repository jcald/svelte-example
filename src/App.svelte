<script>
	let count=0
</script>

<button on:click={()=>count++}>
	Increment
</button>
<button on:click={()=>count--}>
	Decrement
</button>
<button on:click={()=>count=0}>
	Reset
</button>

<h2>
	{count}
</h2>



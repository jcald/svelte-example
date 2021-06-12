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

<style>
h2 {
	font-size: 4em;
	color:rgb(255, 30, 0);
}
button {
    background-color: rgb(241, 198, 3);
    border-radius: 4px;
    font-size: 4em;
    padding: 0.2em 0.5em;
    border-top: 7px solid rgba(255,255,255,0.5);
    border-left: 7px solid rgba(255,255,255,0.5);
    border-right: 7px solid rgba(0,0,0,0.2);
    border-bottom: 7px solid rgba(0,0,0,0.2);
    color: #f55;
  }

</style>

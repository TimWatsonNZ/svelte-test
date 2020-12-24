<script>
	let count = 0;

	function handleClick() {
		count += 1;
	}
</script>

<style>
	h1 {
		color: purple;
	}
</style>

<button>
	Clicked {count} {count === 1 ? "time" : "times"}
</button>
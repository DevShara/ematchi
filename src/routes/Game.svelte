<script>
	import Grid from './Grid.svelte';

	let size;
	let grid = [];
	let found = [];
</script>

<div class="game">
	<div class="info" />

	<div class="grid-container">
		<Grid />
	</div>

	<div class="info" />
</div>

<style>
	.game {
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
		height: 100%;
		font-size: min(1vmin, 0.5rem);
	}

	.info {
		width: 80em;
		height: 10em;
		background-color: aqua;
	}

	.grid-container {
		width: 80em;
		height: 80em;
		background-color: bisque;
	}
</style>

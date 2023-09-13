<script>
	import Board from '../lib/Board.svelte';

	const boards = [
		{ id: 0 },
		{ id: 1 }
	];
</script>

<main>
	{#each boards as board (board.id)}
		<Board/>
	{/each}
<main>

<style>

</style>
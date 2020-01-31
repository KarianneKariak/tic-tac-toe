<script>
	import Board from "./Board.svelte";
	const title = "Tic Tac Toe";
</script>
<style>
	.wrapper_game {
		display: flex;
		flex-direction: column;
		align-items: center;
		width: 100%;
	}
</style>

<svelte:head>
	<title>{title}</title>
</svelte:head>

<div class="wrapper_game">
<h1>{title}</h1>
<Board/>
</div>

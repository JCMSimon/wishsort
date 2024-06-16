<script>
	export let gameId = 0

	let embedIframe
		
	function addGameToList() {
		// call addTolist function in the lib file that does the smart stuff with gameId -> returns next gameId
		// replace      [  this  ]     with the function
		// let newGameId = gameId + 1
		// embedIframe.src = `https://store.steampowered.com/widget/${newGameId}`
	}
</script>

<button class="embedButton" on:click={addGameToList}>
	<iframe bind:this={embedIframe} src="https://store.steampowered.com/widget/{gameId}/" class="embedIframe" title="Game" scrolling="no" frameborder="0"></iframe>
</button>

<style>
	.embedButton {
		border: none;
		background-color: transparent;
		width: 50vw;
		height: 17vh;
		scale: 1.5;	
		cursor: pointer;
		border-radius: var(--rounding);
	}
	
	.embedIframe {
		width: 100%;
		height: 100%;
		pointer-events: none;
		border-radius: var(--rounding);
		z-index: 4;
		user-select: none;
	}
	
</style>
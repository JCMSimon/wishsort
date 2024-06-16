<!-- svelte-ignore a11y-no-static-element-interactions -->
<!-- svelte-ignore a11y-click-events-have-key-events -->
<!-- TODO | update url -->
<div class="layout" on:click={() => location.href = "https://wished.games"}>
	<!-- Add logo -->
	<img src="logo.svg" alt="Wishsort" class="logo">
	<h2 class="logoInText">Wishsort</h2>
</div>

<style>
	.layout {
		display: flex;
		align-items: center;
		cursor: pointer;
		gap: 1vw;
	}
	
	.logoInText {
		color: var(--clr-text);
		font-family: Arial;
		font-size: max(3vw,30px);
		margin: 0;
	}
	
	.logo {
		height: 80%;
	}
</style>
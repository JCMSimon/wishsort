<!-- svelte-ignore a11y-no-static-element-interactions -->
<!-- svelte-ignore a11y-click-events-have-key-events -->
<!-- TODO | update url -->
<div class="layout" on:click={() => location.href = "https://wishsort.tools"}>
	<!-- Add logo -->
	<img src="" alt="Wishsort" class="logo">
	<h2 class="LogoInText">Wishsort</h2>
</div>

<style>
	.layout {
		display: flex;
		gap: 1vw;
		cursor: pointer;
	}
	
	.LogoInText {
		color: var(--clr-text);
		font-family: Arial;
		font-size: max(3vw,30px);
		margin: 0;
	}
</style>
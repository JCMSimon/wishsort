<script>
	import Logo from "$lib/header/Logo.svelte"
</script>

<body>
<header>
	<Logo/>
	if steamid:
		menu / export button here	
</header>

<div class="content">
	if global toggle:
		finished stuff + 1click steam sort button thingy api boom pow
	else:
		if steamid:
			steamslot 1 here 
			<br>
			steamslot 2 here
		else:
			enter steamid	
</div>

<!-- when you click a steam slot it adds it to the list and sets its own iframe to the next id, if there are none left set a global toggle so that we can display the final output -->

<footer>
	footer here
</footer>
</body>

<style>
	header {
		display: flex;
	}
	
	.content {
		display: flex;
		flex-direction: column;
	}
</style>
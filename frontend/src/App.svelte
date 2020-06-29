<script>
	import Nav from './components/Nav.svelte';
</script>

<style>
	main {
		position: relative;
		/* max-width: 56em; */
		padding: 2em;
		margin: 3rem 2rem 0 2rem;
		box-sizing: border-box;
		margin-top: 3rem;
	}

	img.backdrop {
		position: fixed;
		z-index: -1;
		width: 100vw;
		bottom: 0;
		opacity: 0.4;
	}

	footer {
		width: 100%;
		background-color: #e7f7fa;
		font-size: 0.8rem;
		padding: 0.5rem;
		box-sizing: border-box;				
		display: flex;		
	}

	.page {
		display: flex;
		flex-direction: column;
		min-height: 100vh;
		justify-content: space-between;
		align-items: stretch
	}

	footer img {
		height: 0.9rem;
		padding-left: .4rem;	
	}

</style>

<div class="page">
	<Nav />

	<main>
	</main>

	<footer>© 2020 <img src="/netice9.svg" alt="Net Ice 9 Logo"/></footer>
</div>
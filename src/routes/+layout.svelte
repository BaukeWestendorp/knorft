<script lang="ts">
	import '../style/main.css';
	import Header from '../components/Header.svelte';
</script>

<div class="layout">
	<Header />
	<main>
		<slot />
	</main>
	<footer>door Knørft</footer>
</div>

<style>
	.layout {
		margin: 0 auto;
		max-width: 42rem;
		padding: 0 1rem;
	}

	footer {
		border-top: 1px solid var(--secondary);
		height: 3rem;

		display: flex;
		align-items: center;
	}
</style>

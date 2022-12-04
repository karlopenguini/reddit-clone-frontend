<script>
	import Nav from '../../components/Nav.svelte';
	import '../../app.css';
</script>

<div>
	<div>
		<Nav />
	</div>

	<main class="m-auto h-full w-[952px] ">
		<slot />
	</main>
</div>

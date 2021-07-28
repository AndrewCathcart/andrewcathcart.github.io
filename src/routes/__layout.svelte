<script>
	import '../app.postcss';
	import Nav from '../components/nav.svelte';
</script>

<div class="min-h-screen dark:bg-gray-800 dark:text-white">
	<div class="p-8">
		<Nav />
		<slot />
	</div>
</div>

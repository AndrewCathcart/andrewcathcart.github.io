<script lang="typescript">
	import Fa from 'svelte-fa';
	import { faLightbulb as offBulb } from '@fortawesome/free-solid-svg-icons';
	import { faLightbulb as onBulb } from '@fortawesome/free-regular-svg-icons';

	let darkMode = false;
	const toggle = () => {
		darkMode = !darkMode;
		window.document.documentElement.classList.toggle('dark');
	};
</script>

<div on:click={toggle}>
	<Fa
		icon={darkMode ? onBulb : offBulb}
		size="2x"
		class="text-black cursor-pointer dark:text-yellow-400"
	/>
</div>

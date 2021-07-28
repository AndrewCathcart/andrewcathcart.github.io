<script>
	import Fa from 'svelte-fa';
	import { faLinkedin, faGithub } from '@fortawesome/free-brands-svg-icons';
</script>

<svelte:head>
	<title>Andy Cathcart</title>
</svelte:head>

<main>
	<section class="mt-12 mx-12 md:grid md:grid-cols-2 md:gap-4 items-center">
		<div class="flex flex-col md:mr-24">
			<h1 class="text-5xl font-bold text-black my-8 dark:text-white">👋 Hello</h1>
			<p class="text-4xl text-gray-500 font-normal dark:text-gray-400 mb-8">Welcome to my site</p>
			<p class="text-xl leading-7 text-black dark:text-gray-100 text-justify">
				I'm Andy. I'm a Software Engineer based in Newcastle, United Kingdom. At the moment I'm
				working at CEF as a Cloud Software Engineer. I'm also a Computer Science graduate from
				Newcastle University. This is just a place to store my ramblings. Currently a work in
				progress.
			</p>
			<p class="text-xs mt-8 mb-4 invisible md:visible">
				This website was created using
				<a class="text-green-500" href="https://kit.svelte.dev/">SvelteKit</a>,
				<a class="text-green-500" href="https://www.typescriptlang.org/">TypeScript</a>,
				<a class="text-green-500" href="https://tailwindcss.com/">Tailwind CSS</a> + ☕️
			</p>
		</div>
		<div class="mt-8 md:mt-0 flex flex-col items-center">
			<img
				height="400"
				width="400"
				src="/profile.png"
				alt="Andrew Cathcart"
				class="rounded-full w-72"
			/>
			<section class="mt-12 flex gap-4 justify-center">
				<a href="https://github.com/andrewcathcart">
					<Fa icon={faGithub} size="4x" />
				</a>
				<a href="https://www.linkedin.com/in/andrew-cathcart-257030120/">
					<Fa icon={faLinkedin} size="4x" />
				</a>
			</section>
		</div>
	</section>
</main>

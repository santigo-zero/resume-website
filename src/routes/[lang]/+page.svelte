<script lang="ts">
	import { base } from '$app/paths';
	import { page } from '$app/stores';

	$: data = $page.data;
</script>

<main class="text-gray-700">
	<header class="grid grid-cols-1 sm:grid-cols-2 place-content-center gap-4">
		<hgroup class="flex flex-col gap-4">
			<h1 class="text-5xl font-black">SANTIAGO GONZALEZ</h1>
			<h2 class="text-2xl font-black">{data.position}</h2>
		</hgroup>
		<nav class="flex-1">
			<ul class="grid gap-2 my-4 font-medium text-base">
				<li>
					<a class="inline-flex place-items-center" target="_blank" rel="external" href="https://www.santiagogonzalez.dev">
						<img class="h-6 mr-2" src="{base}/logo-light.svg" alt="Personal logo" />
						santiagogonzalez.dev
					</a>
				</li>
				<li>
					<a class="inline-flex place-items-center" target="_blank" rel="external" href="https://www.linkedin.com/in/santiago-gonzalez-62557221b/">
						<svg class="h-6 mr-2" xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 128 128">
							<path
								fill="currentColor"
								d="M116 3H12a8.91 8.91 0 0 0-9 8.8v104.42a8.91 8.91 0 0 0 9 8.78h104a8.93 8.93 0 0 0 9-8.81V11.77A8.93 8.93 0 0 0 116 3zM39.17 107H21.06V48.73h18.11zm-9-66.21a10.5 10.5 0 1 1 10.49-10.5a10.5 10.5 0 0 1-10.54 10.48zM107 107H88.89V78.65c0-6.75-.12-15.44-9.41-15.44s-10.87 7.36-10.87 15V107H50.53V48.73h17.36v8h.24c2.42-4.58 8.32-9.41 17.13-9.41C103.6 47.28 107 59.35 107 75z"
							/>
						</svg>
						LinkedIn
					</a>
				</li>
				<li>
					<a class="inline-flex place-items-center" target="_blank" rel="external" href="https://www.linkedin.com/in/santiago-gonzalez-62557221b/">
						<svg class="h-6 mr-2" xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 128 128">
							<g fill="currentColor">
								<path
									fill-rule="evenodd"
									d="M64 5.103c-33.347 0-60.388 27.035-60.388 60.388c0 26.682 17.303 49.317 41.297 57.303c3.017.56 4.125-1.31 4.125-2.905c0-1.44-.056-6.197-.082-11.243c-16.8 3.653-20.345-7.125-20.345-7.125c-2.747-6.98-6.705-8.836-6.705-8.836c-5.48-3.748.413-3.67.413-3.67c6.063.425 9.257 6.223 9.257 6.223c5.386 9.23 14.127 6.562 17.573 5.02c.542-3.903 2.107-6.568 3.834-8.076c-13.413-1.525-27.514-6.704-27.514-29.843c0-6.593 2.36-11.98 6.223-16.21c-.628-1.52-2.695-7.662.584-15.98c0 0 5.07-1.623 16.61 6.19C53.7 35 58.867 34.327 64 34.304c5.13.023 10.3.694 15.127 2.033c11.526-7.813 16.59-6.19 16.59-6.19c3.287 8.317 1.22 14.46.593 15.98c3.872 4.23 6.215 9.617 6.215 16.21c0 23.194-14.127 28.3-27.574 29.796c2.167 1.874 4.097 5.55 4.097 11.183c0 8.08-.07 14.583-.07 16.572c0 1.607 1.088 3.49 4.148 2.897c23.98-7.994 41.263-30.622 41.263-57.294C124.388 32.14 97.35 5.104 64 5.104z"
									clip-rule="evenodd"
								/>
								<path
									d="M26.484 91.806c-.133.3-.605.39-1.035.185c-.44-.196-.685-.605-.543-.906c.13-.31.603-.395 1.04-.188c.44.197.69.61.537.91zm2.446 2.729c-.287.267-.85.143-1.232-.28c-.396-.42-.47-.983-.177-1.254c.298-.266.844-.14 1.24.28c.394.426.472.984.17 1.255zm2.382 3.477c-.37.258-.976.017-1.35-.52c-.37-.538-.37-1.183.01-1.44c.373-.258.97-.025 1.35.507c.368.545.368 1.19-.01 1.452zm3.261 3.361c-.33.365-1.036.267-1.552-.23c-.527-.487-.674-1.18-.343-1.544c.336-.366 1.045-.264 1.564.23c.527.486.686 1.18.333 1.543zm4.5 1.951c-.147.473-.825.688-1.51.486c-.683-.207-1.13-.76-.99-1.238c.14-.477.823-.7 1.512-.485c.683.206 1.13.756.988 1.237zm4.943.361c.017.498-.563.91-1.28.92c-.723.017-1.308-.387-1.315-.877c0-.503.568-.91 1.29-.924c.717-.013 1.306.387 1.306.88zm4.598-.782c.086.485-.413.984-1.126 1.117c-.7.13-1.35-.172-1.44-.653c-.086-.498.422-.997 1.122-1.126c.714-.123 1.354.17 1.444.663zm0 0"
								/>
							</g>
						</svg>
						GitHub
					</a>
				</li>
				<li>
					<a class="inline-flex place-items-center" href="mailto:santiagogonzalezbogado@gmail.com">
						<svg class="h-6 mr-2" xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24">
							<path
								fill="currentColor"
								d="M20 4H4c-1.1 0-1.99.9-1.99 2L2 18c0 1.1.9 2 2 2h16c1.1 0 2-.9 2-2V6c0-1.1-.9-2-2-2zm-.4 4.25l-7.07 4.42c-.32.2-.74.2-1.06 0L4.4 8.25a.85.85 0 1 1 .9-1.44L12 11l6.7-4.19a.85.85 0 1 1 .9 1.44z"
							/>
						</svg>
						santiagogonzalezbogado@gmail.com
					</a>
				</li>
			</ul>
		</nav>
	</header>
	<br />
	<section class="mt-2 space-y-2">
		<h3 class="font-black text-3xl">
			{data.experience.title}
		</h3>
		<ol>
			{#each data.experience.list as experience}
				<li class="mt-1 space-y-1 text-2xl font-bold">{experience.position}</li>
				<li class="mt-1 space-y-1 text-2xl font-bold">{experience.company}, {experience.from_to}</li>
				<li class="mt-1 space-y-1 text-xl font-bold">&mdash; {experience.project}</li>
				<li class="mt-1 space-y-1 text-lg font-medium">{experience.description}</li>
			{/each}
		</ol>
	</section>
	<div class="grid grid-cols-1 sm:grid-cols-2 place-content-center gap-4 mt-6">
		<section class="mt-2 space-y-2">
			<h3 class="font-black text-3xl">{data.education.title}</h3>
			<ol>
				{#each data.education.list as job}
					<li class="text-lg font-normal">{job.date}</li>
					<li class="text-2xl font-black">{job.at}</li>
					<li class="text-xl font-medium">{job.in}</li>
				{/each}
			</ol>
		</section>
		<section class="mt-2 space-y-2">
			<h3 class="font-black text-3xl">{data.skills.title}</h3>
			<p class="font-medium text-xl">
				{data.skills.description}
				<a class="inline-flex place-items-center" rel="external" target="_blank" href={data.skills.link[1]}
					>{data.skills.link[0]}
					<svg xmlns="http://www.w3.org/2000/svg" width="22" height="22" viewBox="0 0 24 24">
						<path fill="currentColor" d="M14 3v2h3.59l-9.83 9.83l1.41 1.41L19 6.41V10h2V3m-2 16H5V5h7V3H5a2 2 0 0 0-2 2v14a2 2 0 0 0 2 2h14a2 2 0 0 0 2-2v-7h-2v7Z" />
					</svg>
				</a>
			</p>
			<ol class="text-lg font-medium columns-2 mt-2 space-y-2 list-disc list-inside">
				<li>React(NextJS)</li>
				<li>Svelte(SvelteKit)</li>
				<li>Node</li>
				<li>Git</li>
				<li>Javascript(ES6+)</li>
				<li>Typescript</li>
				<li>CI/CD</li>
				<li>SQL</li>
			</ol>
		</section>
	</div>
</main>

<style>
	@import url('https://fonts.googleapis.com/css2?family=Manrope:wght@200;300;400;500;600;700;800&family=PT+Sans:ital,wght@0,400;0,700;1,400;1,700&display=swap');

	:global(body) {
		font-family: 'Manrope', sans-serif;
	}

	@media print {
		@page {
			size: A4;
		}
	}

	main {
		display: grid;
		grid-template-rows: auto auto 1fr;
		width: min(210mm, 100%);
		min-height: min(297mm, 100vh);
		margin-inline: auto;
		padding-top: 0.5in;
		padding-bottom: 0.5in;
		padding-left: 1.2cm;
		padding-right: 2.1cm;
		outline: 1px gray solid;
	}
</style>

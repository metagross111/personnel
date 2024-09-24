<template>
	<footer class="text-gray-400 dark:text-gray-600 text-sm text-center pb-8 sm:flex sm:justify-between">
		<div class="text-primary-400 dark:text-primary-300">
			© <span v-text="new Date().getFullYear()" /> Mohit Sarsahay 
			<span class="inline-block ml-1">
				<img src="https://upload.wikimedia.org/wikipedia/commons/4/41/Flag_of_India.svg" alt="Indian Flag" class="w-5 h-5 inline-block" />
			</span>
		</div>
		<div />
		<div class="sm:text-right text-primary-400">
			Built with <a
				href="https://nuxt.com/"
				class="text-primary-700 dark:text-primary-100 underline"
				target="_blank"
				rel="noopener"
				title="The Intuitive Vue Framework"
			>Nuxt Js</a> & <a
				href="https://ui.nuxt.com/"
				target="_blank"
				rel="noopener"
				title="A UI Library for Modern Web Apps"
				class="text-primary-700 dark:text-primary-100 underline"
			>Nuxt UI</a>
		</div>
	</footer>
</template>

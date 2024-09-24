<template>
	<div class="space-y-6">
		<NuxtImg
			src="/avtar.webp"
			alt="Mohit Sarsahay"
			class="ring-2 border ring-gray-200 border-gray-300 dark:ring-white/10 dark:border-gray-800 hover:ring-4 transition-all duration-300 bg-gray-200 dark:bg-gray-900 rounded-full h-12 w-12 sm:h-24 sm:w-24"
			placeholder
			width="45"
			format="webp"
			loading="lazy"
		/>
		<h1 class="text-xl font-bold tracking-tight text-gray-800 dark:text-gray-100">
			Hello there! 👋
		</h1>
		<h2 class="h-2 font-semibold text-xl text-gray-800 dark:text-gray-100">
			<mark class="bg-primary-300">Mohit Sarsahay.</mark>
		</h2>
		<p class="text-gray-900 dark:text-gray-400">
			I’m a second-year Computer Science student with over two years of experience in application development, specializing in web technologies.
		</p>
		<p class="text-gray-900 dark:text-gray-400">
			My primary skills include Java, Spring Boot, JavaScript, and MongoDB. I’m currently learning Nuxt.js and open to collaborating on software projects to achieve your goals.
		</p>
		<p class="text-gray-900 dark:text-gray-400">
			If you're interested in my projects or want to read my articles, feel free to follow me and subscribe to my newsletter, where I share regular updates on my work and insights.
		</p>
		<p class="text-gray-900 dark:text-gray-400">
			<span class="animated-text">Let's build something worth sharing</span>
		</p>
	</div>
</template>

<script setup lang="ts">
import { useSeoMeta } from '#imports';

useSeoMeta({
	title: 'Mohit Sarsahay',
	description:
      'I\'m a second-year Computer Science student and software engineer from India, believing computer science is the best way to solve problems using systematic approaches and algorithms.',
});
</script>

<style scoped>
.animated-text {
  background: linear-gradient(-45deg, #ee7752, #e73c7e, #23a6d5, #23d5ab);
  background-size: 300%;
  font-weight: bold;
  font-size: 1.2em;
  -webkit-background-clip: text;
  background-clip: text;
  -webkit-text-fill-color: transparent;
  animation: gradient 5s ease infinite;
}

@keyframes gradient {
  0% { background-position: 0% 50%; }
  50% { background-position: 100% 50%; }
  100% { background-position: 0% 50%; }
}
</style>

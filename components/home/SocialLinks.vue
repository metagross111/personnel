<template>
	<div>
		<h2 class="uppercase text-xs font-semibold text-gray-400 mb-4">
			Socials
		</h2>
		<div class="flex space-x-4">
			<NuxtLink
				v-for="link in links"
				:key="link.icon"
				:to="link.url"
				target="_blank"
				external
				:aria-label="link.name + ' profile'"
				class="flex items-end gap-4 hover:text-primary-300 group"
			>
				<Icon
					:name="link.icon"
					class="w-8 h-8"
				/>
			</NuxtLink>
		</div>
	</div>
</template>

<script setup lang="ts">
const links = [
	{
		name: 'GitHub',
		url: 'https://github.com/mohit07dec',
		icon: 'mdi:github',
	},
	{
		name: 'Linkedin',
		url: 'https://www.linkedin.com/in/mohit-sarsahay-565852230/',
		icon: 'mdi:linkedin',
	},
	{
		name: 'Discord',
		url: 'https://discordapp.com/users/206875427631923200',
		icon: 'mdi:discord',
	},
	{
		name: 'Email',
		url: 'mailto:mohit.dev.workspace@gmail.com',
		icon: 'mdi:email',
	},
];
</script>

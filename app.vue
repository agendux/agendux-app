<template>
    <div>
		<NuxtPage/>
    </div>
</template>


<script setup>
import '@/public/assets/css/config.css'
useHead({
	title: 'Agendux - App de Agendamento',
	script: [
		{
			src: 'https://kit.fontawesome.com/e6e181ff2b.js',
			crossorigin: 'anonymous',
			defer: true
		}
	]
})
</script>

<template>
	<div class="h-full flex flex-row justify-center items-center">
		<div class="flex flex-col text-center items-center">
			<div>
				<img width="100" src="/favicon.ico" alt="Logo Agendux" />
			</div>
			<br>

			<h1>App em Desenvolvimento</h1>
			<p>Estamos trabalhando para lançar o Agendux o quanto antes. Fique ligado!</p>
			<span class="dot">
				Agendux é um aplicativo open source para agendamentos simples, rápidos e seguros.<br>
				Pensado para profissionais e pequenos negócios que querem uma solução leve, moderna e focada na
				privacidade do usuário.
			</span>
			<div class="icons">
				<a href="https://github.com/agendux/agendux-app"><Icon name="uil:github" size="2em" style="color: white;" /></a>
				<a href="https://www.linkedin.com/company/agendux/"><Icon name="uil:linkedin" size="2em" style="color: white;" /></a>
			</div>
		</div>
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

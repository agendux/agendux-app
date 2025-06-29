


<template>
  <!--- 
    <div>
      <NuxtRouteAnnouncer />
      <NuxtWelcome />
    </div>
  --->
  
<div class="wrapper">
  <center>
  <img width="100" src="/favicon.ico" alt="Logo Agendux" />
  <br>

  <h1>App em Desenvolvimento</h1>
  <p>Estamos trabalhando para lançar o Agendux o quanto antes. Fique ligado!</p>
    <span class="dot">
  Agendux é um aplicativo open source para agendamentos simples, rápidos e seguros.<br>
      Pensado para profissionais e pequenos negócios que querem uma solução leve, moderna e focada na privacidade do usuário.
      </span>
  <div class="icons">
    <a href="https://github.com/agendux/agendux-app"><i class="fa fa-github"></i></a>
    <a href="https://www.linkedin.com/company/agendux/"><i class="fa fa-linkedin"></i></a>
  </div>
  </center>
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

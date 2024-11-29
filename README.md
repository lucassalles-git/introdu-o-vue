<h1>Blog de Primeiro Contato com Vue.js</h1>
Este repositório contém uma página de blog desenvolvida como atividade inicial para explorar o Vue.js, um framework progressivo para construção de interfaces de usuário.

📋 O que foi abordado?
1️⃣ O que é Vue.js?
O Vue.js é um framework de JavaScript focado em criar interfaces de usuário de forma simples e reativa. Ele permite criar aplicações web modernas com uma abordagem declarativa e flexível, sendo ideal tanto para projetos pequenos quanto grandes.

2️⃣ O Quadro Progressivo
Vue é considerado um framework progressivo, o que significa que você pode começar com funcionalidades básicas e ir adicionando mais conforme necessário, como roteamento e gerenciamento de estado. Essa progressividade facilita a adoção do Vue em projetos já existentes.

3️⃣ Componentes de Arquivo Único (SFCs)
No Vue.js, os Single File Components (SFCs) são arquivos .vue que reúnem o HTML, CSS e JavaScript de um componente em um único lugar. Essa abordagem organiza melhor o código e facilita a manutenção.

Exemplo básico de um SFC:

<template>
  <div>
    <h1>{{ mensagem }}</h1>
  </div>
</template>

<script>
export default {
  data() {
    return {
      mensagem: "Bem-vindo ao meu blog com Vue.js!",
      };
    },
  };
</script>

<style>
h1 {
  color: #42b983; /* Cor oficial do Vue.js */
}
</style>
🚀 Tecnologias Utilizadas
Vue.js
HTML e SASS
JavaScript

Acesse o projeto no navegador:
https://introducao-vue.vercel.app/

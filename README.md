<h1>Blog de Primeiro Contato com Vue.js</h1>
Este repositório contém uma página de blog desenvolvida como atividade inicial para explorar o Vue.js, um framework progressivo para construção de interfaces de usuário.

<h2>📋 O que foi abordado?<h2/>
<h3>1️⃣ O que é Vue.js?</h3>
<p>O Vue.js é um framework de JavaScript focado em criar interfaces de usuário de forma simples e reativa. Ele permite criar aplicações web modernas com uma abordagem declarativa e flexível, sendo ideal tanto para projetos pequenos quanto grandes.</p>

<h3>2️⃣ O Quadro Progressivo<h3/>
<p>Vue é considerado um framework progressivo, o que significa que você pode começar com funcionalidades básicas e ir adicionando mais conforme necessário, como roteamento e gerenciamento de estado. Essa progressividade facilita a adoção do Vue em projetos já existentes.</p>

<h3>3️⃣ Componentes de Arquivo Único (SFCs)<h3/>
<p>No Vue.js, os Single File Components (SFCs) são arquivos .vue que reúnem o HTML, CSS e JavaScript de um componente em um único lugar. Essa abordagem organiza melhor o código e facilita a manutenção.</p>

<p>Exemplo básico de um SFC:</p>

```
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

```

<h3>🚀 Tecnologias Utilizadas<h3/>
<ul>
<li>Vue.js<li/>
<li>HTML e SASS<li/>
<li>JavaScript<li/>
</ul>

<p>Acesse o projeto no navegador:</p>
<a href = "https://introducao-vue.vercel.app/" target = "_blank">Introdução Vue<a/>

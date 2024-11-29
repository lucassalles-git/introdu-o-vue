<h1>Blog de Primeiro Contato com Vue.js</h1>
Este repositório contém uma página de blog desenvolvida como atividade inicial para explorar o Vue.js, um framework progressivo para construção de interfaces de usuário.

📋 <h2>O que foi abordado?<h2/>
1️⃣ O que é Vue.js?
O Vue.js é um framework de JavaScript focado em criar interfaces de usuário de forma simples e reativa. Ele permite criar aplicações web modernas com uma abordagem declarativa e flexível, sendo ideal tanto para projetos pequenos quanto grandes.

2️⃣ <h2>O Quadro Progressivo<h2/>
Vue é considerado um framework progressivo, o que significa que você pode começar com funcionalidades básicas e ir adicionando mais conforme necessário, como roteamento e gerenciamento de estado. Essa progressividade facilita a adoção do Vue em projetos já existentes.

3️⃣ <h2>Componentes de Arquivo Único (SFCs)<h2/>
No Vue.js, os Single File Components (SFCs) são arquivos .vue que reúnem o HTML, CSS e JavaScript de um componente em um único lugar. Essa abordagem organiza melhor o código e facilita a manutenção.

Exemplo básico de um SFC:

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

🚀 <h2>Tecnologias Utilizadas<h2/>
• Vue.js <br>
• HTML e SASS <br>
• JavaScript

Acesse o projeto no navegador:
<a href = "https://introducao-vue.vercel.app/" target = "_blank">Introdução Vue<a/>

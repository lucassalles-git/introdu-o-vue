<script setup>//Lógica
</script>

<template> <!--HTML, Tags-->
  <header>
    <h1><img class="logo" src="/src/assets/Vue.js_Logo_2.svg.png" alt="">Vue<span>.js</span></h1>

    <input type="text" placeholder="Pesquisar no blog">

  </header>

  <main>
    <section class="conteiner">

      <section class="info">
        <h2>O que é Vue?​</h2>

        <p>
          Vue (pronuncia-se /vjuː/, como view ) é um framework JavaScript para construir interfaces de usuário. Ele é
          construído sobre HTML, CSS e JavaScript padrão e fornece um modelo de programação declarativo baseado em
          componentes que ajuda você a desenvolver eficientemente interfaces de usuário de qualquer complexidade.
        </p>
      </section>

      <section class="info">
        <h2>O Quadro Progressivo​</h2>

        <p>
          Vue é um framework e ecossistema que cobre a maioria dos recursos comuns necessários no desenvolvimento
          frontend. Mas a web é extremamente diversa - as coisas que construímos na web podem variar drasticamente em
          forma e escala. Com isso em mente, o Vue foi projetado para ser flexível e adotável incrementalmente.
        </p>
      </section>

      <section class="info">
        <h2>Componentes de arquivo único​</h2>

        <p>
          Na maioria dos projetos Vue habilitados para ferramentas de construção, criamos componentes Vue usando um
          formato de arquivo semelhante a HTML chamado Single-File Component (também conhecido como *.vuefiles,
          abreviado
          como SFC ). Um Vue SFC, como o nome sugere, encapsula a lógica do componente (JavaScript), template (HTML) e
          estilos (CSS) em um único arquivo.
        </p>
      </section>

    </section>
  </main>

</template>

<style>
/* Estilos globais */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
</style>

<style scoped lang="scss">
/*Stilos*/

header {
  height: 30vh;
  padding: 64px 322px;

  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  gap: 48px;


  color: #42B883;
  background-color: #17171A;

  .logo {
    margin-right: 8px;
    width: 40px;
  }

  h1 {
    font: 600 40px sans-serif;
  }

  span {
    color: rgba(255, 255, 255, 0.747);
  }

  input {
    width: 1216px;
    height: 56px;
    padding: 16px 24px;

    border: 2px solid #6d757233;
    border-radius: 8px;
    background-color: #252529;

    font: 500 20px sans-serif;
    color: #AFABB6;

    transition: all 0.4s;
    
  }

  input:focus{
    border: 2px solid #42b8835b;
    outline: none;

    transition: all 0.4s;
  }
}

main {

  display: flex;
  justify-content: center;
  background-color: #121214;
}

.conteiner {
  height: 100%;
  padding: 80px 0;

  display: flex;
  flex-direction: column;
  gap: 40px;
}

.info {
  width: 1216px;
  height: 243px;
  padding: 0 40px;

  display: flex;
  flex-direction: column;
  justify-content: center;
  gap: 16px;

  border: 2px solid #42b88333;
  border-radius: 8px;

  background-color: #17171A;
  color: white;
  font-family: "Inter", serif;
  font-weight: 500;

  transition: all 0.4s;

  h2 {
    font-size: 24px;
  }

  p {
    line-height: 32px;
    font-size: 20px;
    color: #AFABB6;
  }
}

.info:hover{
    transition: all 0.4s;
    border: 2px solid #42b883;
  }
</style>

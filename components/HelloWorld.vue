<template>
    <div class="hello">
      <h1>Bem vindo ao seu template</h1>
      <h1>I'm Diva!</h1>
    <h2>Aqui será mostrado um pouco da pandemia em forma de memes.</h2> 
    <br>
    <h2>Os estudos...</h2>
    <div class="container" style="width: 100%;">
      <img src="img/gr.jpg" alt="imagemgr" width="1080" height="720">
    </div>
    </div>
    <br>
    <h2>O pessoal foi para a rua sem a permissão...</h2>
    <div class="high">
      <img src="img/ygonamoura.jpg" alt="imagemygona" width="720" height="460">
    </div>
    <h2>O twitter parou com o rato frito...</h2>
    <div class="size">
      <img src="img/aghata.jpg" alt="imagemaghata" width="580" height="">
    </div>
  <br>
  <video width="320" height="240" controls>
      <source src="ygv.mp4" type="video/mp4">
    </video>
    <input name="pesquisaCep" id="pesquisaCep" type="number">
    <input type="button" name="Pesquisar" onclick="buscarEnderecoNoViaCEP()" value="Pesquisar">
  <br>
  <br>
    <h1>The best scale</h1>
    <br>
  <table>
      <tr>
          <th>Nome</th>
          <th>Ano</th>
          <th>Meme</th> 
      </tr>
      <td>Aula Online</td>
          <td>2022</td>
          <td><div class="v" style="width: 100%;">
            <img src="img/gr.jpg" alt="imagemgr" width="500" height="400">
          </div>
        </td>
      <tr>
          <td>Partiu ygonamoura</td>
          <td>2021</td>
          <td>  <div class="v">
            <img src="img/ygonamoura.jpg" alt="imagemygona">
          </div>  </td>
        </tr>
            <td>Aghata Nunes borracheira</td>
            <td width="50" height="50">2020</td>
            <td>  <div class="v">
              <img src="img/aghata.jpg" alt="imagemaghata">
            </div>   </td>
  
            <tr>
              <td>Uma diva Trabalhadora </td>
              <td>2021</td>
              <td>  
           <video width="320" height="240" controls>
                <source src="trabalhadora.mp4" type="video/mp4" width="500" height="800">
              </video>
                </td>
      </tr>
  </table>
  
  
  
      
  </template>
  
  <script>
  export default {
    name: 'HelloWorld',
    props: {
      msg: String
    }
  }
  </script>
  
  <!-- Add "scoped" attribute to limit CSS to this component only -->
  <style scoped>
  h1{
    color: #42b983;
  }
  h3 {
    margin: 40px 0 0;
  }
  ul {
    list-style-type: none;
    padding: 0;
  }
  li {
    display: inline-block;
    margin: 0 10px;
  }
  a {
    color: #42b983;
  }
  table {
      width: 100%;
      border-collapse: collapse;
  }
  th, td {
      border: 1px solid #dddddd;
      text-align: left;
      padding: 8px;
  }
  th {
      background-color: #f2f2f2;
  }
  </style>
  
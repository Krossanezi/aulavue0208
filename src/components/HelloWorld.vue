<template>
<div class="hello">
    <h1>Bem vindo ao seu template</h1>
<br>

  <h2>Aqui será mostrado um pouco da pandemia em forma de memes.</h2> 
  <br>
  <br>
  <br>  
  <div class="container" style="width: 100%;">
    
    <img src="@/assets/gr.jpg" alt="imagemgr" width="300" height="300">
  </div>
  </div>
    <!--
  <br>
  <h2>O pessoal foi para a rua sem a permissão...</h2>
  <div class="high">
    <img src="@/assets/ygonamoura.jpg" alt="imagemygona" width="720" height="460">
  </div>
  <h2>O twitter parou com o rato frito/ Agatha Nunes borracheira...</h2>
  <div class="size">
    <img src="@/assets/aghata.jpg" alt="imagemaghata" width="580" height="">
  </div>
<br>
<video width="320" height="240" controls>
    <source src="@/assets/ygv.mp4" type="video/mp4">
  </video>
-->

  <br>
<br><br><br><br><br><br><br>

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
        <td><div class="v" style="width: 40%; height: 400px;" >
         <img src="@/assets/gr.jpg" alt="imagemgr" width="700" height="400">
        </div>
      </td>
    <tr>
        <td>Partiu ygonamoura</td>
        <td>2021</td>
        <td>  <div class="v" style= "width:10%;">
          <img src="@/assets/ygonamoura.jpg" alt="imagemygona">
        </div>  </td>
      </tr>
          <td>Aghata Nunes borracheira</td>
          <td width="10%" height="50">2020</td>
          <td>  <div class="v">
            <img src="@/assets/aghata.jpg" alt="imagemaghata">
          </div>   </td>

          <tr>
            <td>Voando como uma Boleleta</td>
            <td>2021</td>
            <td>  
         <video width="70%" height="400px" controls>
              <source src="@/assets/ygv.mp4" type="video/mp4" width="500" height="800">
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
  color:hwb(153 12% 66%);
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
  color: hwb(153 12% 66%);
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
.banner{
    height: 100vh;
    background: linear-gradient( rgba(0,0,0,0.281), rgba(0,0,0,0.308)),url;
    background-size: cover;
    background-position: center;
    background-repeat: no-repeat;
    display: flex;
    align-items: center;
    justify-content: center;
    text-align: center;
}
.texto .titulo{
    color: #fff;
    font-size: 60px;
    font-weight: 600;
}
.texto .sub_titulo{
    color: #fff;
    font-size: 58px;
    font-weight: 600;
}
.texto .botoes{
    margin-top: 30px;
}
.texto .botoes button{
    height: 55px;
    width: 170px;
    border-radius: 5px;
    border: 0;
    margin: 0 10px;
    font-size: 20px;
    font-weight: 500;
    padding: 0 10px;
    cursor: pointer;
    outline: none;
    transition: 0.3s;
}
.texto .botoes button.n-overlay{
    color: white;
    background: none;
    border: 2px solid white;
}
.texto .botoes button.n-overlay:hover{
    color: black;
    background-color: white;
}
.texto .botoes button.overlay{
    background: white;
    color: black;
    animation: vibrar 0.5s ease-in-out infinite both;
}
</style>

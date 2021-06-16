# Rajahir1.github.io
<head>
<title>Mi página personal</title>
<style>
h1 {
  text-align: center; color: blue; font-family: "Times New Roman";
} 

h2,h3,h4 {
  background-color: lightblue; color: blue; font-family: "Times New Roman";
}

p {
  font-family: "Arial"; text-align: justify;
}

th {
  background-color: lightblue;
}

* {
  box-sizing: border-box;
}

input[type=text], select, textarea {
  width: 50%;
  padding: 12px;
  border: 1px solid #ccc;
  border-radius: 4px;
  resize: vertical;
}

label {
  padding: 12px 12px 12px 0;
  display: inline-block;
}

input[type=Enviar] {
  background-color: Blue;
  color: white;
  padding: 12px 12px;
  border: none;
  border-radius: 4px;
  cursor: pointer;
  float: right;
}

input[type=Enviar]:hover {
  background-color: #45a049;
}

.container {
  border-radius: 5px;
 
  padding: 10px;
}

.col-25 {
  float: left;
  width: 10%;
  margin-top: 6px;
}

.col-75 {
  float: left;
  width: 75%;
  margin-top: 6px;
}

/* Clear floats after the columns */
.row:after {
  content: "";
  display: table;
  clear: both;
}

/* Para mayor información contáctanos:  {
  .col-25, .col-75, input[type=submit] {
    width: 100%;
    margin-top: 0;
  }



</style>
</head>

<body>
<br>
<h1>Raj Ahir</h1> 
<br>
<center> <img src="Raj Ahir.jpg" width="200" height="200" alt="Raj Ahir"  align = "center"> </center>
<br>
<h2>Biografía</h2>
<p>  Raj Mukeshbhai Ahir, Nació el 01 de diciembre de año 2002. Es de nacionalidad India.Culminó sus estudios escolares en la escuela The Oxford School Santiago, en bachiller de Ciencias.</p>
<hr>      
<h2>Favoritos</h2>
<h3>Platos</h3>
<ul>
<li>Arroz con Pollo</li>
<li>Arroz con leche</li>
<li>Tres leche</li>
</ul>
<h3>Pasatiempos</h3>
<ol>
<li>Escuchar Música</li>
<li>Viajar</li>
<li>Leer Libros</li>
</ol>     
<h3>Canciones</h3>
<center><table  border="1">
<tr>
<th>Genero</th>
<th>Nombre</th>
<th>Autor</th>
<th>Audio</th>
</tr>
<tr>
<td>Instrumental</td>
<td>Saibo</td>
<td>Shreya Ghosal</td>
<td><audio controls>
  <source src="Saibo.ogg" type="audio/ogg">
  <source src="Saibo.mp3" type="audio/mpeg">
Your browser does not support the audio element.
</audio></td>
</tr>
<tr>
<td>Instrumental</td>
<td>Ilahi</td>
<td>Pritam</td>
<td><audio controls>
  <source src="Ilahi.ogg" type="audio/ogg">
  <source src="Ilahi.mp3" type="audio/mpeg">
Your browser does not support the audio element.
</audio></td>
</tr>
<tr>
<td>Reggaeton</td>
<td>Sau Aasmaan</td>
<td>Armaan</td>
<td><audio controls>
  <source src="Sau Aasmaan.ogg" type="audio/ogg">
  <source src="Sau Aasmaan.mp3" type="audio/mpeg">
Your browser does not support the audio element.
</audio></td>
</tr>
</table></center>
<h3>Libro</h3>
<center> <img src="Harry.jpg" width="200" height="200" alt="Harry Potter"  align = "center"> </center>
<br>
<center><a href="https://en.wikipedia.org/wiki/Harry_Potter_and_the_Philosopher%27s_Stone">Haary Potter and Sorcerer's Stone</a></center>

<h3>Película</h3>
<br>
<center> <img src="Kedarnath.jpg" width="320" height="240" alt="Raj Ahir"  align = "center"> </center>
<br>
<center><video width="320" height="240" controls>
  <source src="Trailer.mp4" type="video/mp4">
  <source src="Trailer.ogg" type="video/ogg">
Your browser does not support the video tag.
</video></center>
<br>
<h3>Para mayor información contáctanos:</h3>
<div class="container">
  <form action="/action_page.php">
  <div class="row">
    <div class="col-25">
      <label for="fname">Nombre</label>
    </div>
    <div class="col-75">
      <input type="text" id="fname" name="Nombre" placeholder="Su Nombre..">
    </div>
  </div>
  <div class="row">
    <div class="col-25">
      <label for="lname">Correo</label>
    </div>
    <div class="col-75">
      <input type="text" id="lname" name="Correo" placeholder="Su Correo..">
    </div>
  </div>
  <div class="row">
    <div class="col-25">
      <label for="country">Asunto</label>
    </div>
    <div class="col-75">
      <input type="text" id="country" name="Asunto" placeholder="Su Asunto..">
    </div>
  </div>
  <div class="row">
    <div class="col-25">
      <label for="subject">Mensaje</label>
    </div>
    <div class="col-75">
      <textarea id="subject" name="Mensaje" placeholder="Escriba su mensaje.." style="height:200px"></textarea>
    </div>
  </div>
<br>
  <div class="row">
    <input type="button" value="Enviar">
  </div>
  </form>
</div>

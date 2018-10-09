# JavaHouse
JavaScript projects, simple code
<!DOCTYPE html>
<html>
<head>
<link rel="stylesheet" href="style.css">s”>
<body bgcolor="black">
<h2>Casa con JavaScript</h2>
</head>
<body>
<img id="myImage" src="mansion.jpg" style="width:1000px">
<div>
<embed src="zombie.mp3" autoplay="null" loop="false" width="200" height="70""></embed>
<button onclick="document.getElementById('myImage').src='abrirpuerta.jpg'">Entrar a la casa</button>
<button onclick="document.getElementById('myImage').src='cerrarpuerta.jpg'">CerrarPuerta</button>
<button onclick="document.getElementById('myImage').src='salir.jpg'">Salir</button>
<button onclick="document.getElementById('myImage').src='bombillon.jpg'">Bombillo On</button>
<button onclick="document.getElementById('myImage').src='bombillof.jpg'">Bombillo Off</button>
</div>

<p id="demo">Caracteristicas</p>
<p id="demo1">Area</p>
<script>

function area(p1, p2) {
    return p1 * p2;
}
document.getElementById("demo1").innerHTML = area(100,50);

var Casa = {
    Nombre : "Nightmare",
    Color  : "gris",
    Altura       : 50,
    Base       : 100,
    Puertas  : 2
};

document.getElementById("demo").innerHTML =
Casa.Nombre + " es " + Casa.Color + " con " + Casa.Altura + " metros de alto " +Casa.Base + " metros de base y " + Casa.Puertas + " Dos puertas: Una trasera y una delantera ";


</script>

</body>
</html>

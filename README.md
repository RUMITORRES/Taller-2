Taller-2
========
<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="iso-8859-1"
<meta name="description" content="Ejemplo de HTML5">
<meta name="keywords" content="HTML5, CSS3, JavaScript">
<title> Taller 1 </title>
 
 
<link rel="stylesheet" herf="misestilos.css"><!-- Esta linea de codigo sirve para llamar las hojas de estilos css -->
 
 
<!-- Funcion para identificar numero par e impar  -->
<script type="text/javascript"> 
var num = prompt("Ingresa un numero");
 
var Resultado = parImpar(num);
alert("El numero "+num+" es "+Resultado);
 
function parImpar(numero) {
  if(num % 2 == 0) {
    return " par ";
  }
  else {
    return " impar ";
  }
}
</script>

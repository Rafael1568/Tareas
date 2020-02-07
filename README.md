# Tareas
var mes=10;
var nombre= ("Rafael Alberto Martínez Ramírez");
var carné= ("18003869");
if (mes == 12 || mes == 1 || mes == 2){
  alert("Es invierno");
} else if (mes >= 3 && mes <= 5){
  alert("Es primavera");
} else if (mes >= 6 && mes <= 8){
  alert("Es Verano");
} else if (mes >= 9 && mes <= 11){
  alert("Es otorño");
} else{
  alert("No existe");
} 
document.write("Mi número de carné es:" + carné + "<br> Mi nombre es:" + nombre);

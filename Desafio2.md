#DESAFIO 2

//Crear una función que muestre "¡Hola, mundo!" en la consola.

function saludo () {
  console.log('¡Hola, mundo!');
}

saludo();

//Crear una función que reciba un nombre como parámetro y muestre "¡Hola, [nombre]!" en la consola.

function saludo (nombre) {
  console.log(`¡Hola, ${nombre)!`);
}

saludo('Ana');

//Crear una función que reciba un número como parámetro y devuelva el doble de ese número.

function valor (numero) {
  return numero * 2;
}

let valorDoble = valor(6);
console.log(valorDoble);

//Crear una función que reciba tres números como parámetros y devuelva su promedio.

function promedio (x, y, z) {
  return (x + y + z)/ 3;
}

let promedioFinal = promedio(3, 9, 6);
console.log(promedioFinal);

//Crear una función que reciba dos números como parámetros y devuelva el mayor de ellos.

function encontrarMayor(a, b) {
  return a > b ? a : b;
}

let numeroMayor = encontrarMayor(5, 10);
console.log(numeroMayor);

//Crear una función que reciba un número como parámetro y devuelva el resultado de multiplicar ese número por sí mismo.

function valor (numero) {
  return numero * numero;
}

let resultado = valor(4);
console.log(resultado);

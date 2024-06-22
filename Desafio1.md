# DESAFIO 1

//Cambia el contenido de la etiqueta h1 con document.querySelector 
//y asigna el siguiente texto: "Hora del Desafío".

#JS:
let titulo = document.querySelector('h1');
titulo.innerHTML = 'Hora del Desafío';

//Crea una función que muestre en la consola el mensaje "El botón fue clicado" siempre 
//que se presione el botón "Console".

#HTML:
<button onclick="intentoDeUsuario();" class="button">Console</button>

#JS:
function intentoDeUsuario() {
    alert('Clic desde el botón');
}

//Crea una función que se ejecute cuando se haga clic en el botón "prompt", preguntando el nombre 
//de una ciudad de Brasil. Luego, muestra una alerta con el mensaje concatenando la respuesta con 
//el texto: "Estuve en {ciudad} y me acordé de ti".

#HTML:
<button onclick="nombreCiudadBrasil();" class="button">Prompt</button>

#JS:
function nombreCiudadBrasil() {
    let ciudad = prompt('Ingresa el nombre de una ciudad de Brasil:');
    alert(`Estuve en ${ciudad} y me acordé de ti.`);
}

//Crea una función que muestre una alerta con el mensaje: "Yo amo JS" siempre que se presione el botón "Alerta".

#HTML:
<button onclick="mensajeAlerta();" class="button">Alert</button>

#JS:
function mensajeAlerta() {
    alert('Yo amo JS')
}

//Al hacer clic en el botón "suma", pide 2 números y muestra el resultado de la suma en una alerta.

#HTML:
<button onclick="numeros();" class="button">Suma</button>

#JS:
function numeros() {
    let numero1 = parseInt(prompt('Ingresa un primer numero:'));
    let numero2= parseInt(prompt('Ingresa un segundo numero:'));
    let suma = numero1 + numero2
    alert(`La suma entre ${numero1} y ${numero2} es de ${suma}.`);
}

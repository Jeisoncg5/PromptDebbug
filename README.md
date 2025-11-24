## Actividad Prompt para Debbug

vas a actuar como un docente de programación con enfoque en JavaScript, donde a manera de pregunta y respuesta me ayudaras con este codigo.

Contexto:
Soy estudiante de programación, donde actualmente me estoy enfocando en el lenguaje de JavaScript, específicamente Vanilla. He estado realizando pequeños ejercicios como esta calculadora de consola.

Entrada
Voy a pasarte el codigo, con el fin de que me expliques a nivel de casa de estudio como funciona dicho codigo y que me realices una correccion si esta es necesaria.

Salida
me responderás con una explicacion del codigo, donde si es necesario realizaras la debida correccion o mejora.

## Codigo / Ejemplo

let num1 = parseFloat(prompt("Ingresa el primer número:"));
let num2 = parseFloat(prompt("Ingresa el segundo número:"));
let operacion = prompt("Elige operación (+, -, *, /):");

let resultado;

if (operacion === "+") {
  resultado = num1 + num2;
} else if (operacion === "-") {
  resultado = num1 - num2;
} else if (operacion === "*") {
  resultado = num1 * num2;
} else if (operacion === "/") {
  resultado = num1 / num2;
} else {
  alert("Operación no válida");
}

alert("Resultado: " + resultado);

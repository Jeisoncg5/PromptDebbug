# Actividad Prompt para Debbug

vas a actuar como un docente de programación con enfoque en JavaScript, donde a manera de pregunta y respuesta me ayudaras con este codigo.

### Contexto

Soy estudiante de programación, donde actualmente me estoy enfocando en el lenguaje de JavaScript, específicamente Vanilla. He estado realizando pequeños ejercicios como esta calculadora de consola.

### Entrada

Voy a pasarte el codigo, con el fin de que me expliques a nivel de casa de estudio como funciona dicho codigo y que me realices una correccion si esta es necesaria.

### Salida

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

alert("Resultado:)
------


## Prompt 2


### Contexto:

Vas a actuar como un docente experto en programación con enfoque en JavaScript (Vanilla). Tu objetivo es ayudarme a entender cómo funciona un fragmento de código que te proporcionaré. Quiero que me expliques el funcionamiento como si estuvieras enseñándomelo en un ambiente académico, claro y detallado. Además, si el código necesita correcciones o puede mejorarse, debes indicarlo.

### Entrada:

Te proporcionaré un código JavaScript. Necesito que me expliques de forma pedagógica cómo funciona, línea por línea o por bloques si es necesario. También quiero que identifiques errores, malas prácticas o puntos que se puedan mejorar. Si es necesario, reescribas el código corregido o mejorado.

### Salida:

Me responderás con:

Una explicación clara y educativa del funcionamiento del código.

1. Una corrección si el código contiene errores.

2. Una versión mejorada del código si aplica.


### Código

let palabra = prompt("Ingresa una palabra:");

let palabraInvertida = palabra
  .split("")
  .reverse()
  .join("");

if (palabra === palabraInvertida) {
  alert("Es un palíndromo");
} else {
  alert("No es un palíndromo");
}

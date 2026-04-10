# Datos Dinámicos

## Variables
Agregarle movimiento a nuestros sketch de p5.js, exiten variables que vienen integradas y tambien se pueden crear nuevas:

* Posición del mouse: Sintaxis (mouseX,mouseY) por ejemplo ellipse(mauseX,maouseY,100100); variables del sistema númerico que determinan la posición del mouse en coordenadas eje x, eje y.

## Crea tus propias variables
 1. Declarar tu variable -- círculoMorado=0 Al inicio del codigo function setup
 2. Inicializa tu variable --  CirculoMorado = circuloMorado+1; Function draw
 3. Usa tu variable

Para declarar tu variable podemos usar __let__ para variables dinámicas y _const_ para variables constantes

## Javascript Objects

Nos serviran para crear nuestro código de una forma adecuada y ordenada.

Es la forma de agrupar muchas variables dentro de una variable.

Es una estructura de datos que te permite agrupar valores relacionados bajo un mismo nombre. En lugar de tener muchas variables sueltas, los objetos funcionan como "contenedor" que organiza la información mediante pares y claves.

## random();function
 Es una variable que ya viene incorporada en p5.js su trabajo es devolver un número aleatorio dentro de un rango que tú definas.

 * __random()__
   let tamañoCuadrado;
let bordeCuadrado;
function setup() {
  createCanvas(400, 400);
  background(183, 112, 255);
  frameRate(10);
  
}

function draw() {
  tamañoCuadrado = random (20,400);
  bordeCuadrado = random (1,20);
 
  rectMode(CENTER);
  stroke(74,114,247); // agregar alpha 10
  strokeWeight(bordeCuadrado);
  fill(2245, 0, 255);
  square(200,200, tamañoCuadrado)

* 

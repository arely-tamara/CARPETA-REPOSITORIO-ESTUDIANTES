## Aclaraciones antes de seguir...
  1. En Github existen diferentes tipos de archivo que uno puede crear, para formato marckdown deben usar __.md__ en el nombre del archivo.
  2. Llevar al día las bitacoras de forma ordenanda.
  3. Para agregar código de p5.js ´´´ .

## 4 Pilares
  1. Descomposición: "Dividir para conquistar" Consiste en tomar un problema grande y complejo y romperlo en partes más pequeñas y manejables.
     
     * En diseño: Si quieres ver la "Brecha salarial"; no programas todo de una vez. Primero diseñas "Sueldo A", luego "Sueldo B" luego "Interacción" y finalmente fondo
    
  2. Reconocimiento de patrones: "Encontrar similitudes" Es observar o regularidades dentro de un problema. Si algo se repite o sigue una lógica constante se puede automatizar.
     
     * En diseño:

  3. Abstracción: crear una representación simbolica de la realidad

     * En diseño: por ej. para representar la "presión social" quizas un circulo qeu se achica cuando el mouse se mueve representa eso.
       
     * En el código:
    
  4. Algoritmos: "La receta paso a paso" Es el diseño de una serie de reglas ordenadas para resolver el problema o "Plan de acción".
     *

## Tipos de interacción:

  1. Interacción discreta(eventos): Es cuando ocurre

# Funciones propias:

Permite dar:
  1. Modularidad.
  2. Reusabilidad.

### Funcion -- function(){ 

  * Sintaxis: function Nombredelafunción(){}
    

     * function draw(){
       background(147,104,166);
       DibujarFiguras();
       }
´´´

let x=0
let y=0
let speed = 3;

function setup() {
  createCanvas(400, 400);
}

function draw() {

background(111, 255, 71);

noStroke();

fill(207, 30, 217); //asigna color rgb

ellipse(x,200,100,100); //

x=x+speed
  
if(x > width || x < 0) {

print("fueradecuadro")

speed = speed * -1;

}

y=y+speed
  
noStroke();

fill(30, 217, 186);

ellipse(200,y,100,100);
  
if(y > width || y < 0) {

print("fueradecuadro")

speed = speed * -1;
     
}

´´
  
}

# SoloLearn 
Respuestas a los miniquiz
### 1
* [] Los caracteres que se usan para iniciar una variable son las  letras
* [] para genear una consola solo debemos poner console.log("¡JS es genial ! ");
* [] para poder formar un codigo valido solo debemos poner <script>, nombre "james"; console.log (nombre); al final el </script>.

### 2
* [] El resultado de intentar hacer referencia a un miembro de la matriz que no existe es indefinido 
* [] ingresando var example = new Array(); creamos una matriz vacia que se pueda llenar en cualquire momento despues.
* []Array tiene la propiedad "length", porque es un objeto. 

### 3
* [] En el objeto matematico,¿cual de los siguentes metodos se usa paracalcular la raiz? sqrt
* [] ¿cuales de estos nombres son aceptables para la variables de javaScript? _modulo y primer modulo


### 4
* [] para generar "js is cool!" a la consola: console.log ("¡JS es genial!");
* [] ¿Que dos palabras clave necesitamos para crear una matriz? nuevo y formacion


### proyectos del curso
Trip Planner


You need to plan a road trip. You are traveling at an average speed of 40 miles an hour.
Given a distance in miles as input (the code to take input is already present), output to the console the time it will take you to cover it in minutes.

Sample Input:
150

Sample Output:
225

solucion: function main() {
    var distance = parseInt(readLine(), 10);
    //tu código va aquí
    let resultado = distance /40 *60;
    console . log("", resultado );
}
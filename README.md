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

### proyecto 2
The Snail in the Well


The snail climbs up 7 feet each day and slips back 2 feet each night.
How many days will it take the snail to get out of a well with the given depth?

Sample Input:
31

Sample Output:
6

Explanation: Let's break down the distance the snail covers each day:
Day 1: 7-2=5
Day 2: 5+7-2=10
Day 3: 10+7-2=15
Day 4: 15+7-2=20
Day 5: 20+7-2=25
Day 6: 25+7=32
So, on Day 6 the snail will reach 32 feet and get out of the well at day, without slipping back that night.

solucion:
function main() {
    var depth = parseInt(readLine(), 10);
    //tu código va aquí
    
    var dia = 0;
    var total = 0;
    while(total<depth){
        dia = dia + 1;
        total = total + 7;
        if(total >=depth){
            console.log(dia);
            break;
        }
        total = total - 2;
    }
}

### proyecto 3
Currency Converter


You are making a currency converter app.
Create a function called convert, which takes two parameters: the amount to convert, and the rate, and returns the resulting amount.
The code to take the parameters as input and call the function is already present in the Playground.
Create the function to make the code work.

Sample Input:
100
1.1

Sample Output:
110


solucion:
function main() {
    var cantidad = parseFloat(readLine(), 10);
    var tasa = parseFloat(readLine(), 10);
    
    console.log(convertir(cantidad, tasa));
}
function convertir (cantidad,tasa){
	return cantidad * tasa 
}

### proyecto 4
You are working on a Contact Manager app.
You have created the contact object constructor, which has two arguments, name and number.
You need to add a print() method to the object, which will output the contact data to the console in the following format: name: number
The given code declares two objects and calls their print() methods. Complete the code by defining the print() method for the objects.

solucion:
[10:22 p. m., 29/5/2021] Edmon: function contact(name, number) {
    this.name = name;
    this.number = number;
    this.print = () =>{
    console.log(this.name+": "+this.number);
  }
}

var a = new contact("David", 12345);
var b = new contact("Amy", 987654321)
a.print();
b.print();
[10:22 p. m., 29/5/2021] Edmon: function main() {
    var aumentar = parseInt(readLine(), 10);
    var precio = [98.99, 15.2, 20, 1026];
    //your code goes here
    for (i = 0; i < precio.length; i++) {
        precio[i] += aumentar;
    }

    console.log(precio);
}
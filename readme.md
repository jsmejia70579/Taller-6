# Proyecto de Programacion 4

_Este serie de archivos estan los trabajos propuestos y debidamente desarrollados_

## Participantes 🚀

Juan Salvador Mejia Diaz
Jorge Armando Gonzalez

## Ejercicio1

```javascript
var unNombre= prompt("registre su nombre"); 
alert("ahora esta en la matrix"+ unNombre)
}
```
![I1](https://github.com/jsmejia70579/Taller-6/blob/master/imagenes/1.png)

## Ejercicio2

```javascript
varnumero1=+prompt("ingrese el valor1");
var numero2=+prompt("ingrese el valor2");
var resultado=numero1+numero2;
alert(resultado)
}
}
```
![I1](https://github.com/jsmejia70579/Taller-6/blob/master/imagenes/2.png)

## Ejercicio3

```javascript
var numero1=+prompt("ingrese el valor1");
var numero2=+prompt("ingrese el valor2");
var resultado=numero1+numero2;
alert(resultado)
var numero3=prompt("ingrese el valor3");
var resultado2=resultado*numero3;
alert(resultado2)

}
}
```
![I1](https://github.com/jsmejia70579/Taller-6/blob/master/imagenes/3.png)

## Ejercicio4

```javascript
var kilometros=prompt("ingrese los kilometros");
var combustible=+prompt("listros de combustible");
var kilometros1=kilometros/combustible;
alert("su consumo por kilometros es"+kilometros1
}
}
```
![I1](https://github.com/jsmejia70579/Taller-6/blob/master/imagenes/4.png)

## Ejercicio5

```javascript
var fahrenheit=prompt("ingrese los grados fahrenheit");
var celsius=(5/9)
var resultado=(5/9)*(fahrenheit-32);
alert(resultado)
}
}
```
![I1](https://github.com/jsmejia70579/Taller-6/blob/master/imagenes/5.png)

## Ejercicio6

```javascript
var numero1=+prompt("ingrese el valor1");
var numero2=+prompt("ingrese el valor2");
var numero3=+prompt("ingrese el valor3");
var promedio=numero1+numero2+numero3;
var resultado=promedio/3;
alert(resultado)
}
}
```
![I1](https://github.com/jsmejia70579/Taller-6/blob/master/imagenes/6.png)

## Ejercicio7

```javascript
var numero=(parseFloat(prompt("ingrese un valor"))*(85/100))
console.log("el valor es"+numero);
alert(numero)
}
}
```
![I1](https://github.com/jsmejia70579/Taller-6/blob/master/imagenes/7.png)
## Ejercicio8

```javascript
var palabra1=prompt("ingrese una palabra");
var palabra2=prompt("ingrese una palabra");
var resultado=palabra1+" "+palabra2;
alert(resultado)
}
}
```
![I1](https://github.com/jsmejia70579/Taller-6/blob/master/imagenes/8.png)

## Ejercicio9

```javascript
var texto=prompt("ingrese un texto")
console.log("el resultado" + texto.charAt(0))
var numero =prompt("ingrese un numero entre 0 y "+texto.length)
console.log( "resultado es"+ texto.charAt(numero))
alert(texto)
alert(numero

}
}
```
![I1](https://github.com/jsmejia70579/Taller-6/blob/master/imagenes/9.png)

## Ejercicio10

```javascript
var shows = parseInt(prompt("Ingrese el numero de Shows"));
if(shows > 3)
    {
        alert(true)
    }
else
{
    alert(false)
}
}
}
```
![I1](https://github.com/jsmejia70579/Taller-6/blob/master/imagenes/10.png)
## Ejercicio11

```javascript
var numeros = parseInt(prompt("Ingrese fecha"));
var texto = numeros.toString()
var date = texto.substr(0,2) + "/" + texto.substr(2,2) + "/" + texto.substr(4,4)
alert(date)
}
}
```
![I1](https://github.com/jsmejia70579/Taller-6/blob/master/imagenes/11.png)

## Ejercicio12

```javascript
var par = parseInt(prompt("Ingrese un valor"));
if(par %2 == 0)
{
    alert(true)        
}
else
{
    alert(false)
}
}
}
```
![I1](https://github.com/jsmejia70579/Taller-6/blob/master/imagenes/12.png)

## Ejercicio13

```javascript
var numero1=prompt("ingrese la edad");
var numero2=+prompt("ingrese cantidad de articulos");
if (numero1>18 && numero2>1){
	alert("true"+ " " +("numero de articulos"+numero2))

}
else {
	alert("false"+ " " +("numero de articulos"+numero2))
}
}
}
```
![I1](https://github.com/jsmejia70579/Taller-6/blob/master/imagenes/13.png)

## Ejercicio14

```javascript
var texto = prompt("Ingrese un texto");
if(texto.length %2 == 1) 
{
    alert(true)
}
else
{
    alert(false)
}
}
}
```
![I1](https://github.com/jsmejia70579/Taller-6/blob/master/imagenes/14.png)

## Ejercicio15

```javascript
var palabra1 = prompt("Ingrese la Palabra 1");
var palabra2= prompt("Ingrese la Palabra 2");
if(palabra1.length < palabra2.length)
{
    alert(true)
}
else
{
    alert(false)
}
}
}
```
![I1](https://github.com/jsmejia70579/Taller-6/blob/master/imagenes/15.png)

## Ejercicio16

```javascript
var nombre1 = prompt("Ingrese Primer Nombre");
var nombre2 = prompt("Ingrese segundo Nombre");
if(nombre1.charAt(0).toLowerCase() == nombre2.charAt(0).toLowerCase())
{
    alert(true);
}
else if(nombre1.charAt((nombre1.length -1)).toLowerCase() == nombre2.charAt((nombre2.length -1)).toLowerCase())
{
    alert(true);
}
else
{
    alert(false);
} 
}
}
```
![I1](https://github.com/jsmejia70579/Taller-6/blob/master/imagenes/16.png))

## Ejercicio17

```javascript
var numero1 = parseInt(prompt("Ingrese un Numero"));
if(numero1<0)
{
    numero1 = numero1 * (-1);
    alert("valor Absoluto "+numero1)
}
else
{
    alert("valor Absoluto "+numero1)
}
}
}
```
![I1](https://github.com/jsmejia70579/Taller-6/blob/master/imagenes/17.png)

## Ejercicio18

```javascript
var numero1 = +parseFloat(prompt("ingrese el primer numero"))
var numero2 = +parseFloat(prompt("ingrese el primer numero"))

if(numero1 > numero2){
	alert("el valor mas grande es "+ numero1)
}
else{
	alert("el valor mas grande es "+ numero2)
}
}
}
```
![I1](https://github.com/jsmejia70579/Taller-6/blob/master/imagenes/18.png)

## Ejercicio19

```javascript
var numero1 = prompt("ingrese una letra")

if(numero1.legenth>1){
	alert("se ingreso mas de un caracter")
}
else if (numero1 == 'A' || 'E' || numero1 == 'I' || numero1 == 'O' || numero1=='U'){
	alert("es vocal")
}
else{
	alert("no es vocal")
}
}
}
```
![I1](https://github.com/jsmejia70579/Taller-6/blob/master/imagenes/19.png)

## Ejercicio20

```javascript
var numero1 = parseInt(prompt("Ingrese Primer Numero"));
var numero2 = parseInt(prompt("Ingrese Segundo Numero"));
var numero3 = parseInt(prompt("Ingrese Tercer Numero"));
if(numero1 < numero2 && numero1 < numero3) {
    console.log("El numero menor es: " + num1)
}
if (numero2 < numero1 && numero2 < numero3) {
    alert("El numero menor es: " + numero2)
}
if(numero3 < numero1 && numero3 < numero2) {
    alert("El numero menor es: " + numero3)
}
}
}
```
![I1](https://github.com/jsmejia70579/Taller-6/blob/master/imagenes/20.png)


# ActEnClase-ConvertirFuncionAFuncionDeFlecha

## Lineas de codigo

## ArrowFuctions.js
Se declara un objeto llamado sacha
```javascript
var sacha = {
```
Se declara la variable nombre del objeto, cuyo valor es "Sacha"
```javascript
nombre: 'Sacha',
```
Se declara la variable apellido del objeto, cuyo valor es "Smith"
```javascript
apellido: "Smith",
```
Se declara la variable edad del objeto, cuyo valor es 26
```javascript
edad: 26,
```
Se declara la variable ingeniero del objeto, cuyo valor es true
```javascript
ingeniero: true,
```
Se declara la variable cocinero del objeto, cuyo valor es false
```javascript
cocinero: false,
```
Se declara la variable cantamnte del objeto, cuyo valor es false
```javascript
cantante: false,
```
Se declara la variable dj del objeto, cuyo valor es false
```javascript
dj: false,
```
Se declara la variable guitarrista del objeto, cuyo valor es false
```javascript
guitarrista: false,
```

Se declara la variable drone del objeto, cuyo valor es true
```javascript
drone: true
```
Se cierra el objeto
```javascript
}
```
Se abre para escribir un comentario. Se declara la funcion imprimirSiEsMayorDeEdad, con parametro de persona
```javascript
/*function imprimirSiEsMayorDeEdad (persona) {
```
Se declara un para comprobar si la edad de la persona en mayor a 17
```javascript
if (persona.edad > 17){
```
Este mensaje solo se mostrar si la condicion de if se cumple
```javascript
console.log(${persona.nombre} es mayor de edad);
```
Se cierra el if, y se abre un else
```javascript
} else {
```
Este mensaje solo se mostrara si la condicion del if no se cumple
```javascript
console.log(${persona.nombre} es menor de edad);
```
Se cierra el else
```javascript
}
```
Se cierra la funcion imprimirSiEsMayorDeEdad. Las lineas de ser un comentario
```javascript
}*/
```
Se declara una constante llamada MAYORIA_DE_EDAD con un valor 18
```javascript
const MAYORIA_DE_EDAD = 18;
```
Se abre para escribir lineas como comentario. Se declara la funcion esMayorDeEdad, y el parametro es persona
```javascript
/*function esMayorDeEdad (persona) {
```
Se regresara si la edad de la persona es mayor a MAYORIA_DE_EDAD
```javascript
return persona.edad > MAYORIA_DE_EDAD;
```
Se dejan de escribir lineas como comentarios
```javascript
}*/
```
Esto es un comentario
```javascript
//funcion anonima
```
Se abre para lineas como comentarios. Se declara una constante llamada a esMayorDeEdad que es igual a funcion(persona)
```javascript
/*const esMayorDeEdad = function (persona) {
```
Regresa si la edad de la persona es mayor a MAYORIA_DE_EDAD
```javascript
return persona.edad > MAYORIA_DE_EDAD;
```
Se cierra para dejar de escribir lineas como comentarios
```javascript
}*/
```
Esto es un comentario
```javascript
//Arrow function
```
Se declara una constante llamda a esMayor de edad que es igual a persona y es igual o mayor o que la edad de la persona que es mayor a MAYORIA_DE_EDAD
```javascript
const esMayorDeEdad = persona => persona.edad > MAYORIA_DE_EDAD;
```
Esto es un comentario. Se declara una constante llamada esMayorDeEdad2 que igual a la edad del objeto que es igual a mayor que edad que es mayor que MAYORIA_DE_EDAD
```javascript
//const esMayorDeEdad2 = ({edad}) => edad > MAYORIA_DE_EDAD;
```
Se declara una funcion llamada imprimirSiEsMayorDeEdad, y el parametro es persona
```javascript
function imprimirSiEsMayorDeEdad (persona) {
```
Se declara un if, con la condicion esMayorDeEdad(persona)
```javascript
if (esMayorDeEdad(persona)){
```
Este mensaje solo se mostrar si se cumple la condicion del if
```javascript
console.log(`${persona.nombre} es mayor de edad`);
```
Se cierra el if. Se abre el else el caso de que no se cumpla el if
```javascript
} else {
```
Este mensaje solo se mostrara si la condicion del if no se cumple
```javascript
console.log(`${persona.nombre} es menor de edad`);
```
Se cierra el else
```javascript
}
```
Se cierra la funcion
```javascript
}
```
Esto es un comentario
```javascript
//Crear una funcion que nos de acceso o no, segun la edad de la persona.
```
Esto es un comentario
```javascript
//Corregir la funcion
```
Se declara una funcion llamada permitirAcceso y el parametro es persona
```javascript
function permitirAcceso(persona) {
```
Se abre un if con la condicion !esMayorDeEdad(persona)
```javascript
if(!esMayorDeEdad(persona)){
```
Este mensaje solo se mostrara si la condicion del if se cumple
```javascript
console.log(`Acceso Denegado`);
```
Se cierra el if
```javascript
}
```
Se cierra la funcion llamada permitirAcceso
```javascript
}
```
Esto es un comentario
```javascript
//Elaborar funcion de flecha
```
Se declara una constante llamada Acceso_A_Persona que es igual a persona que eso es igual o mayor que la edad del objeto que es menor que MAYORIA_DE_EDAD
```javascript
const Acceso_A_Persona = persona => persona.edad < MAYORIA_DE_EDAD;
```
Se declara una funcion llamada OtorgarAcceso, el parametro es persona
```javascript
function OtorgarAcceso(persona){
```
Se declara un if con la condicion Acceso_A_Persona(persona)
```javascript
if(Acceso_A_Persona(persona)){
```
Este mensaje solo se mostrara si la condicion de if se cumple
```javascript
console.log(`Acceso Denegado`);
```
Se cierra el if
```javascript
}
```
Se Cierra la funcion llamada OtorgarAcceso
```javascript
}
```

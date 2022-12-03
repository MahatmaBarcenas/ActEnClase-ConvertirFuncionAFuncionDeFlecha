# ActEnClase-ConvertirFuncionAFuncionDeFlecha

## Lineas De Codigo

## ArrowFunctions.js
var sacha = {
    nombre: 'Sacha',
    apellido: "Smith",
    edad: 26,
    ingeniero: true,
    cocinero: false,
    cantante: false,
    dj: false,
    guitarrista: false,
    drone: true
}

/*function imprimirSiEsMayorDeEdad (persona) {
    if (persona.edad > 17){
        console.log(${persona.nombre} es mayor de edad);        
    } else {
        console.log(${persona.nombre} es menor de edad);    
    }
}*/

const MAYORIA_DE_EDAD = 18;

/*function esMayorDeEdad (persona) {
    return persona.edad > MAYORIA_DE_EDAD;
}*/

//funcion anonima
/*const esMayorDeEdad = function (persona) {
    return persona.edad > MAYORIA_DE_EDAD;
}*/

//Arrow function
const esMayorDeEdad = persona => persona.edad > MAYORIA_DE_EDAD;

//const esMayorDeEdad2 = ({edad}) => edad > MAYORIA_DE_EDAD;


function imprimirSiEsMayorDeEdad (persona) {
    if (esMayorDeEdad(persona)){
        console.log(`${persona.nombre} es mayor de edad`);        
    } else {
        console.log(`${persona.nombre} es menor de edad`);    
    }
}

//Crear una funcion que nos de acceso o no, segun la edad de la persona.
//Corregir la funcion

function permitirAcceso(persona) {
    if(!esMayorDeEdad(persona)){
        console.log(`Acceso Denegado`);
    }
}

//Elaborar funcion de flecha

const Acceso_A_Persona = persona => persona.edad < MAYORIA_DE_EDAD;

function OtorgarAcceso(persona){
    if(Acceso_A_Persona(persona)){
        console.log(`Acceso Denegado`);  
    }
}

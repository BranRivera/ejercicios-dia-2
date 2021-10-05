# ejercicios-dia-2


/*
let numero = prompt("Ingrese un numero");

function ejercicioCinco(numero) {
    if ((numero >= 5) && (numero <= 10)) {
        for(let i = numero - 1; i >= 1; i--) {
            numero = numero * i;
        } console.log(numero) 
    } else if (numero < 5) {
        console.log(Math.abs(numero));
    } else if (numero > 10) {
        numero = numero * 2;
        alert(numero)
    }
}

ejercicioCinco(numero);
*/
/*
let edadUsuario = prompt("Ingrese su edad");
let bebida = prompt("Ingrese una bebida entre cerveza, jugo y agua");
let billeteCliente
let vuelto
*/
/*
function validarEdad(a,b,c,d) {
    if (a < 18 && b == "cerveza") {
        alert("Sos menor de edad, no podés realizar la compra!")
    } else {
        c = prompt("El costo es de $50. Ingrese con cuanto va a pagar")
        d = 50 - c
        if (c < 50) {
            alert("Error. Pague con otro billete de mayor valor")
        } else {
        alert("Su vuelto es de $" + d);
    }
} }
validarEdad(edadUsuario,bebida,billeteCliente,vuelto);
*/

/*
let horas = prompt("Escriba las horas que quiera: ");
let minutos = prompt("Escriba los minutos que quiera: ");
let segundos = prompt("Escriba los segundos que quiera: ");


function conversion(h,m,s){
    h = parseInt(h) * 3600;
    m = parseInt(m) * 60;
    s = s;
    alert("la conversion de horas a segundos es: " +h);
    alert("la conversion de minutos a segundos es: " +m);
    alert("los segundos puestos eran: " +s);
}

conversion(horas,minutos,segundos);
*/


const notas = [];

let i = 0;

let resultado = 0

do {
    notas.push(prompt("ingrese las notas del promedio: "))
    let suma = notas.reduce((previo, actual));
    resultado = suma / notas.length;
    i++;
} while (i < 10)

console.log(resultado);

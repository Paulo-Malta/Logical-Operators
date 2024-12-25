var n1 = window.prompt("Digite um valor Booleano (true ou false)");
var n2 = window.prompt("Digite outro valor Booleano (true ou false)");


n1 = n1.toLowerCase() === "true";
n2 = n2.toLowerCase() === "true";


var resultado = n1 || n2;


document.write("<p>Suas variáveis se traduzem no operador lógico || como: <strong>" + resultado + "</strong></p>");

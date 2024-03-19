/*
Senha
*/
/*
var senha;
do{
    senha=prompt("Digite a senha");
}
while(senha!=123);
console.log("Bem vindo ao sistema");
*/
/*
while
*/
/*
console.log("Pares...");
var num = 2;
while(num<=10){
    console.log(num);
    num+=2;
}
*/
/*
for
*/
/*
console.log("Contando...");
for(var i=0;i<5;i++){
    console.log(i);
}
*/
/*
console.log('Tabuada do 3...');
var num = 1
do{
    console.log("3x"+num+"="+num * 3);
    num +=1;
} while (num <=10);
*/
/*
Questão 16
*/
/*
for (let n= 14; n <=30; n++) {
  
    if(n % 2 ===0){
        console.log(n);
        }
    }
*/


/*
Questão 17
*/
/*
function somaDosCemPrimeirosNumeros() {
    let soma = 0; 
    for (let i = 1; i <= 100; i++) {
        soma += i; 
    }
    console.log("A soma dos cem primeiros números inteiros é:", soma);
}
somaDosCemPrimeirosNumeros();
*/
/*
Questão 18
*/
/*
function verificarFaixa(numero) {
    if (numero >= 100 && numero <= 200) {
        console.log("Você digitou um número entre 100 e 200");
    } else {
        console.log("Você digitou um número fora da faixa entre 100 e 200");
    }
}
function verificarNumeros() {
    for (let i = 1; i <= 5; i++) {
        let numero = parseInt(prompt("Digite o número " + i + ":"));
        verificarFaixa(numero);
    }
}
verificarNumeros();
*/

/*
Questão 19
*/
/*
for (let n= 123; n >=75; n--) {
  
    if(n % 2===1){
        console.log(n);
        }
    }
*/
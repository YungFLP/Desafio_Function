# Desafio_Function
alguns exercícios para praticar funções em javascript

function verificarConsole(n1,n2,n3){

    let media = (n1+n2+n3);
    return media;

}

let resultado = verificarConsole(10,8,5);
console.log(`A média é: ${resultado}`);

function verificarAlert(n1,n2){

    let maior = n1 > n2 ? `O número maior é ${n1}`:`O número maior é ${n2}`;
    return maior;

}
let resultMaior = verificarAlert(50,99)
console.log(resultMaior);


function verificarPrompt(n1){

    let mult = (n1*n1);
    return mult;

}let resultMult = verificarPrompt(10);
console.log(resultMult);

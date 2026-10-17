// ex 01

console.log("Olá, mundo");

alert.log("Olá");//Para navegador DOM

// ex 02

const nome ="Maria"; //string
let idade= 18; //inteiro
let altura =1.75; //numeero fracionario
let aprovar = true; //valor logico
let matricula = null; //ausencia intencional de valor

//interpolacao
console.log(`Nome: ${nome}, Idade: ${idade}, Altura: ${altura}`);
//concatenacao
console.log("Nome: " + nome + ", Idade: " + idade + ", Altura " + altura);

//ex 03

let a = 5;
let b = 2;

console.log(a + b);
console.log(a - b);
console.log(a * b);
console.log(a / b);
console.log(a % b);
console.log(a ** b);

//ex 04

let nota1 = 8;
let nota2 = 6;

let media = (nota1 + nota2) / 2;

console.log(media);

//ex 05

let Nome = prompt("Qual é o seu nome?");

alert("Olá, " + Nome + "!");


//Atividade 1

const nomeDoAluno = "Henrique";
let idade = 18;
let curso = "Ciência da Computação";
let semestreAtual = "Segundo semestre";

console.log(`Nome: ${nomeDoAluno}, Idade: ${idade}, Curso ${curso}, Semestre Atual: ${semestreAtual}`);

//Atividade 2

let preco = 25;
let quantidade = Number(prompt("Quantos cadernos você quer comprar:?"));

let precoTotal = (quantidade * preco);

console.log("Preço unitário: " + preco);
console.log("Quantidade: " + quantidade);
console.log(quantidade + " cadernos ficam por: " + precoTotal + " reais");

//Atividade 3

let nota1 = Number(prompt("Digite a primeira nota: "));
let nota2 = Number(prompt("Digite a segunda nota:"));
let nota3 = Number(prompt("Digite a terceira nota:"));

let media = (nota1 + nota2 + nota3) / 3;

console.log("Nota 1: " + nota1);
console.log("Nota 2: " + nota2);
console.log("Nota 3: " + nota3);
console.log("Média final:  " + media);

//Atividade 4

let numero1 = Number(prompt("Digite o primeiro Número:"));
let numero2 = Number(prompt("Digite o segundo Número:"));

console.log("Soma: " + (numero1 + numero2));
console.log("Subtração: " + (numero1 - numero2));
console.log("Multiplicação: " + (numero1 * numero2));
console.log("Divisão: " + (numero1 / numero2));

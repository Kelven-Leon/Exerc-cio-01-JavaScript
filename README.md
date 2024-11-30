# Exerc-cio-01-JavaScript

1)Escreva um programa que peça dois números e exiba a soma deles. 

let num1 = parseFloat(prompt("Digite o primeiro número: "));
let num2 = parseFloat(prompt("Digite o segundo número: "));
console.log("A soma é: " + (num1 + num2));

2)Escreva um programa que peça dois números e exiba a subtração do primeiro pelo segundo.

let num1 = parseFloat(prompt("Digite o primeiro número: "));
let num2 = parseFloat(prompt("Digite o segundo número: "));
console.log("A subtração é: " + (num1 - num2));

3)Escreva um programa que peça dois números e exiba a multiplicação deles.

let num1 = parseFloat(prompt("Digite o primeiro número: "));
let num2 = parseFloat(prompt("Digite o segundo número: "));
console.log("A multiplicação é: " + (num1 * num2));

4)Escreva um programa que peça dois números e exiba a divisão do primeiro pelo segundo.

let num1 = parseFloat(prompt("Digite o primeiro número: "));
let num2 = parseFloat(prompt("Digite o segundo número: "));
console.log("A divisão é: " + (num1 / num2));

5)Escreva um programa que peça dois números e exiba o resto da divisão do primeiro pelo segundo.

let num1 = parseInt(prompt("Digite o primeiro número: "));
let num2 = parseInt(prompt("Digite o segundo número: "));
console.log("O resto da divisão é: " + (num1 % num2));

6)Escreva um programa que incremente o valor de uma variável em 1 e exiba o resultado.

let num = parseInt(prompt("Digite um número: "));
num++;
console.log("Valor incrementado: " + num);

7)Escreva um programa que decremente o valor de uma variável em 1 e exiba o resultado.

let num = parseInt(prompt("Digite um número: "));
num--;
console.log("Valor decrementado: " + num);

8)Atribua o valor de uma variável a outra.

let a = parseFloat(prompt("Digite um valor: "));
let b = a;
console.log("Valor atribuído: " + b);

9)Some 10 a uma variável existente usando o operador +=.

let num = parseInt(prompt("Digite um número: "));
num += 10;
console.log("Resultado após somar 10: " + num);

10)Subtraia 5 de uma variável existente usando o operador -=.

let num = parseInt(prompt("Digite um número: "));
num -= 5;
console.log("Resultado após subtrair 5: " + num);

11)Multiplique o valor de uma variável por 4 usando o operador *=.

let num = parseInt(prompt("Digite um número: "));
num *= 4;
console.log("Resultado após multiplicar por 4: " + num);

12)Divida o valor de uma variável por 2 usando o operador /=.

let num = parseInt(prompt("Digite um número: "));
num /= 2;
console.log("Resultado após dividir por 2: " + num);

13)Obtenha o resto da divisão de uma variável por 3 usando o operador %=.

let num = parseInt(prompt("Digite um número: "));
num %= 3;
console.log("Resto da divisão por 3: " + num);

14)Escreva um programa que verifique se um número é positivo ou negativo.

let num = parseFloat(prompt("Digite um número: "));
if (num >= 0) {
    console.log("Positivo");
} else {
    console.log("Negativo");
}

15)Escreva um programa que verifique se um número é par ou ímpar.

let num = parseInt(prompt("Digite um número: "));
if (num % 2 === 0) {
    console.log("Par");
} else {
    console.log("Ímpar");
}

16)Escreva um programa que verifique qual dos dois números é maior.

let num1 = parseFloat(prompt("Digite o primeiro número: "));
let num2 = parseFloat(prompt("Digite o segundo número: "));
if (num1 > num2) {
    console.log(num1 + " é maior.");
} else if (num2 > num1) {
    console.log(num2 + " é maior.");
} else {
    console.log("Os dois números são iguais.");
}

17)Escreva um programa que verifique se uma pessoa tem mais de 18 anos.

let idade = parseInt(prompt("Qual a sua idade? "));
if (idade >= 18) {
    console.log("Você é maior de idade.");
} else {
    console.log("Você ainda é menor de idade.");
}

18)Escreva um programa que verifique se um número está no intervalo entre 0 e 100.

let num = parseFloat(prompt("Digite um número: "));
if (num >= 0 && num <= 100) {
    console.log("O número está dentro do intervalo.");
} else {
    console.log("O número está fora do intervalo.");
}

19)Escreva um programa que verifique se uma letra é uma vogal ou consoante.

let letra = prompt("Digite uma letra: ").toLowerCase();
if ('aeiou'.includes(letra)) {
    console.log("Vogal");
} else {
    console.log("Consoante");
}

20)Escreva um programa que verifique qual dos três números é o maior.

let n1 = parseFloat(prompt("Primeiro número: "));
let n2 = parseFloat(prompt("Segundo número: "));
let n3 = parseFloat(prompt("Terceiro número: "));
let maior = n1;
if (n2 > maior) maior = n2;
if (n3 > maior) maior = n3;
console.log("O maior número é: " + maior);

21)Escreva um programa que verifique se um ano é bissexto.

let ano = parseInt(prompt("Digite um ano: "));
if ((ano % 4 === 0 && ano % 100 !== 0) || ano % 400 === 0) {
    console.log(ano + " é um ano bissexto.");
} else {
    console.log(ano + " não é um ano bissexto.");
}

22)Escreva um programa que verifique se dois números são positivos.

let num1 = parseFloat(prompt("Digite o primeiro número: "));
let num2 = parseFloat(prompt("Digite o segundo número: "));
if (num1 > 0 && num2 > 0) {
    console.log("Ambos os números são positivos.");
} else {
    console.log("Pelo menos um dos números não é positivo.");
}

23)Escreva um programa que verifique se pelo menos um dos dois números é negativo.

let num1 = parseFloat(prompt("Digite o primeiro número: "));
let num2 = parseFloat(prompt("Digite o segundo número: "));
if (num1 < 0 || num2 < 0) {
    console.log("Pelo menos um dos números é negativo.");
} else {
    console.log("Nenhum dos números é negativo.");
}

24)Escreva um programa que verifique se um número é par e positivo.

let num = parseFloat(prompt("Digite um número: "));
if (num > 0 && num % 2 === 0) {
    console.log("O número é par e positivo.");
} else {
    console.log("O número não é par e positivo.");
}

25)Escreva um programa que verifique se um número não é múltiplo de 5.

let num = parseInt(prompt("Digite um número: "));
if (num % 5 !== 0) {
    console.log("O número não é múltiplo de 5.");
} else {
    console.log("O número é múltiplo de 5.");
}

26)Escreva um programa que verifique se um número está fora do intervalo de 1 a 10.

let num = parseInt(prompt("Digite um número: "));
if (num < 1 || num > 10) {
    console.log("O número está fora do intervalo de 1 a 10.");
} else {
    console.log("O número está dentro do intervalo de 1 a 10.");
}

27)Escreva um programa que verifique se dois números são pares.

let num1 = parseInt(prompt("Digite o primeiro número: "));
let num2 = parseInt(prompt("Digite o segundo número: "));
if (num1 % 2 === 0 && num2 % 2 === 0) {
    console.log("Ambos os números são pares.");
} else {
    console.log("Pelo menos um dos números não é par.");
}

28)Escreva um programa que verifique se a soma de dois números é maior que 100.

let num1 = parseFloat(prompt("Digite o primeiro número: "));
let num2 = parseFloat(prompt("Digite o segundo número: "));
if ((num1 + num2) > 100) {
    console.log("A soma dos números é maior que 100.");
} else {
    console.log("A soma dos números não é maior que 100.");
}

29)Escreva um programa que verifique se dois números são iguais ou diferentes.

let num1 = parseFloat(prompt("Digite o primeiro número: "));
let num2 = parseFloat(prompt("Digite o segundo número: "));
if (num1 === num2) {
    console.log("Os números são iguais.");
} else {
    console.log("Os números são diferentes.");
}

30)Escreva um programa que verifique se uma string não está vazia.

let texto = prompt("Digite uma string: ");
if (texto.trim() !== "") {
    console.log("A string não está vazia.");
} else {
    console.log("A string está vazia.");
}

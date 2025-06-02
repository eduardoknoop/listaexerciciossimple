 ##  *CODIGOS BARBADAS SÓ PRA COLINHA*
### ***Soma de dois valores***
```js
let valor1 = 4;
let valor2 = 5;
let resultado = valor1 + valor2;
console.log(`A soma de ${valor1} + ${valor2} é igual a ${resultado}`);
```
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
### ***Loop while de 1 a 10***
```js
let numero = 1;
while (numero <= 10) {
    console.log(numero);
    numero++;
}
```
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
### ***Verificando se a nota foi aprovada – com if/else***
```js
Copiar
Editar
let nota = 10;
if (nota >= 7) {
    console.log(`Sua nota ${nota} foi aprovada!`);
} else {
    console.log(`Sua nota ${nota} foi reprovada!`);
}
```
- ***Com ternário***
```js
let nota = 10;
let leitura = nota >= 7 ? 'APROVADA' : 'REPROVADA';
console.log(`Sua nota ${nota} foi ${leitura}!`);
```
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
### ***Número aleatório entre 1 e 1000***
```js
let numero = parseInt(Math.random() * 1000 + 1);
console.log(`Seu número aleatório é ${numero}!`);
```
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Basicamente esses foram mini exercicios do curso 1 de JS, explicando quase o basico. Achei interessante colocar eles aqui, para caso de esquecimento eu conseguir me lembrar apenas vendo eles de novo.


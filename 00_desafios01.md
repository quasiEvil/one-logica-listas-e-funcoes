# Resolução dos desafios #1: Funções

1. Criar uma função que exibe "Olá, mundo!" no console.
```javascript
function helloWorld() {
  console.log('Hello, world!');
}

helloWorld();
```
2. Criar uma função que recebe um nome como parâmetro e exibe "Olá, [nome]!" no console.
```javascript
function hello(name) {
  return `Hello, ${name}!`;
}

let greeting = hello('Ana Paula');
console.log(greeting);
```
3. Criar uma função que recebe um número como parâmetro e retorna o dobro desse número.
```javascript
function double(number) {
  return number * 2;
}

let doubleResult = double(5);
console.log(doubleResult);
```
4. Criar uma função que recebe três números como parâmetros e retorna a média deles.
```javascript
function average(a, b, c) {
  return (a + b + c) / 3;
}

let resultAverage = average(10, 9, 5);
console.log(resultAverage);
```
5. Criar uma função que recebe dois números como parâmetros e retorna o maior deles.
```javascript
function biggestNumber(a, b) {
  return Math.max(a, b);
}

let resultBiggestNumber = biggestNumber(10, 42);
console.log(resultBiggestNumber);
```
6. Criar uma função que recebe um número como parâmetro e retorna o resultado da multiplicação desse número por ele mesmo.
```javascript
function squared(number) {
  return number * number;
}

let resultSquared = squared(8);
console.log(resultSquared);
```
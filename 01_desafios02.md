# Resolução dos desafios #2: Funções

1. Crie uma função que calcule o índice de massa corporal (IMC) de uma pessoa, a partir de sua altura, em metros, e peso, em quilogramas, que serão recebidos como parâmetro.

```javascript
function calculadoraIMC(altura, peso) {
  let imc = (peso / (altura * altura)).toFixed(2);
  return imc;
}

calculadoraIMC(1.64, 62); // retorna 23.05

```

2. Crie uma função que calcule o valor do fatorial de um número passado como parâmetro.
```javascript
function fatorial(numero) {
  let n = 1;
  for (let i = 1; i <= numero; i++) {
    n *= i;
  }
  return n;
}
fatorial(5); // retorna 120
```

3. Crie uma função que converte um valor em dólar, passado como parâmetro, e retorna o valor equivalente em reais. Para isso, considere a cotação do dólar igual a R$4,80.
```javascript
function conversor(valorEmUSD){
  let cotacaoUSD = 4.8;
  let valorEmBRL = valorEmUSD * cotacaoUSD
  return valorEmBRL.toFixed(2);
}

conversor(25.4) // retorna 121.92
```

4. Crie uma função que mostre na tela a área e o perímetro de uma sala retangular, utilizando altura e largura que serão dadas como parâmetro.
```javascript
function salaRetangular(altura, largura) {
  let area = altura * largura;
  let perimetro = 2*(altura + largura);
  console.log(`A área da sala é ${area} e o perímetro ${perimetro}`);
}

salaRetangular(5, 10);
```

5. Crie uma função que mostre na tela a área e o perímetro de uma sala circular, utilizando seu raio que será fornecido como parâmetro. Considere Pi = 3,14.
```javascript
function salaCircular(raio) {
  let pi = 3.14;
  let area = (pi * (raio * raio)).toFixed(1);
  let perimetro = (2 * pi * raio).toFixed(1);
  console.log(`A área da sala é ${area} e o perímetro ${perimetro}`);
}

salaCircular(10);
```

6. Crie uma função que mostre na tela a tabuada de um número dado como parâmetro.
```javascript
function tabuada(numero) {
  for (let i = 1; i <= 10; i++) {
    console.log(`${numero} x ${i} = ${numero*i}`);
  }
}

tabuada(5);
```

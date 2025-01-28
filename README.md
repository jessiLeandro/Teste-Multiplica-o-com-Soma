# 📌 Desafio - Multiplicação com Somas (Node.js)

Imagine que você está desenvolvendo uma aplicação onde não é permitido utilizar o operador de multiplicação (*) diretamente. Sua tarefa é criar uma função em Node.js que receba um array de números e calcule o resultado da multiplicação entre todos os seus elementos, utilizando apenas somas.

## Requisitos:
1. A função deve receber um array de números inteiros como entrada.
2. Para multiplicar os números, você deve usar exclusivamente operações de soma.
3. Se o array estiver vazio ou algum elemento não for um número inteiro, a função deve retornar null.
4. Caso o array tenha apenas um elemento, a função deve retornar esse próprio elemento.
5. Certifique-se de tratar casos com números negativos e zeros corretamente.

## Exemplo:
javascript
```
const array = [2, 3, 4];
const resultado = multiplicaComSomas(array);
console.log(resultado); // Saída: 24
```


## Dica:
Lembre-se de que a multiplicação de dois números a e b pode ser vista como somar a, b vezes.

## 🧠 Objetivo:
Explorar conceitos básicos de algoritmos, laços e lógica matemática em JavaScript de forma criativa! 🚀

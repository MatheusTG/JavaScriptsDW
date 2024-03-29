# Variáveis

### Variável de escopo global

```JavaScript
var nome01 = 'Matheus'
```

### Variável de escopo de bloco

```JavaScript
if (true) {
  let idade = 18
}
// Não funciona pois idade só está definido dentro
// do bloco condicional
console.log(idade)
```

### Constante

```JavaScript
const numero = 4

// Não funciona pois não pode alterar o valor de uma constante
numero = '4'
```

# Tipos primitivos

## boolean

Valores booleanos são compostos apenas por 'true' e 'false', e são usados na maior parte das vezes condições

```JavaScript
const condicao = true
if (condicao) {
  console.log('Deu certo')
}
```

## number

Os valores number em JS são formados por números e podem sofrer operações matemáticas

```JavaScript
const num01 = 2
const num02 = 2
console.log(num01 + num02) // 4
console.log(num01 / num02) // 1
```

## string

As strings no JS assim como na maioria das linguagens de programação são formados por caracteres vindos da tabela ASCII

```JavaScript
const nome = 'Matheus'
const sobrenome = 'Teodoro
// Concatenação de strings
const nomeCompleto = nome + ' ' + sobrenome

console.log(nomeCompleto)
```

## undefined

Os valores undefined no JS, como o próprio nome já diz, são formados por valores indefinidos, ou seja valores que ainda nn possuem valores

```JavaScript
const pessoa

// Retorna undefined pois a variável pessoa ainda não possuí um valor definido
console.log(pessoa)
```

## undefined

Os valores undefined no JS, como o próprio nome já diz, são formados por valores indefinidos, ou seja valores que ainda nn possuem valores

```JavaScript
const pessoa

// Retorna undefined pois a variável pessoa ainda não possuí um valor definido
console.log(pessoa)
```

## null

Valores 'null' em JS são indicados pela ausência de valor intencionalmente atribuída

```JavaScript
const resultado = null
if (true) {
  resultado = 2
} else {
  resultado = 4
}
```

## object

Os objetos em JavaScript são estruturas de dados complexas que podem conter diferentes tipos de valores, incluindo números, strings, arrays, funções e outros objetos.

```JavaScript
const pessoa = {
  nome: 'João',
  idade: 30,
  cidade: 'São Paulo'
}

// Acessando propriedades do objeto
console.log(pessoa.nome) // João
console.log(pessoa.idade) // 30

// Adicionando propriedades dinamicamente
pessoa.profissao = 'Engenheiro'

console.log(pessoa.profissao) // Engenheiro
```

## Array

Arrays em JavaScript são objetos especiais usados para armazenar coleções ordenadas de elementos. Os elementos de um array podem ser de qualquer tipo de dados, inclusive outros arrays. Os índices dos arrays começam em 0.

```JavaScript
const numeros = [1, 2, 3, 4, 5]
const nomes = ['João', 'Maria', 'José']

// Acessando elementos do array
console.log(numeros[0]) // 1
console.log(nomes[1]) // Maria

// Adicionando elementos ao array
numeros.push(6)
console.log(numeros) // [1, 2, 3, 4, 5, 6]

// Iterando sobre um array
for (let i = 0; i < numeros.length; i++) {
  console.log(numeros[i])
}
```

## Operadores Básicos

### Aritméticos

Os operadores aritméticos são usados para realizar operações matemáticas básicas.

```JavaScript
let x = 10
let y = 5

console.log(x + y) // Soma: 15
console.log(x - y) // Subtração: 5
console.log(x * y) // Multiplicação: 50
console.log(x / y) // Divisão: 2
console.log(x % y) // Resto da divisão: 0
console.log(++x) // Incremento: 11
console.log(--y) // Decremento: 4
```

## Comparação

Os operadores de comparação são usados para comparar dois valores e retornar um valor booleano.

```JavaScript
let a = 5
let b = 10

console.log(a == b) // Igual a: false
console.log(a != b) // Diferente de: true
console.log(a > b) // Maior que: false
console.log(a < b) // Menor que: true
console.log(a >= b) // Maior ou igual a: false
console.log(a <= b) // Menor ou igual a: true
```

## Lógicos

Os operadores lógicos são usados para combinar duas ou mais expressões e retornar um resultado booleano.

```JavaScript
const condicao1 = true
const condicao2 = false

console.log(condicao1 && condicao2) // E lógico: false
console.log(condicao1 || condicao2) // OU lógico: true
console.log(!condicao1) // NÃO lógico: false
```

## typeof

O typeof em JS é usado para se obter o tipo de algum objeto, ele retorna uma string com o nome do tipo escrito por extenso

```JavaScript
console.log(typeof 'Matheus') // string
console.log(typeof 20) // number
console.log(typeof HTMLElement) // object
```

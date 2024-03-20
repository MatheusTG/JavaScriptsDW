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
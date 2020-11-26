### Português

`funções` ou `functions` é uma forma de você trabalhar um conjunto de código (algorítmo) de forma dinâmica! Mas como assim de forma dinâmica? Isto significa que, por mais que seja o mesmo algorítmo, ele pode se comportar de maneira diferente (dinâmica) para cada tipo de parâmetro recebido, mas vamos com calma. Primeiro, vamos ver como é uma função na prática!

> Algoritmo - Conjunto de código

> Escopo - Conteúdo dentro das chaves `{ ... }`

> Você pode identificar uma função a partir de `()`, uma função normalmente é executada com este simbolo após o nome dela!

Vamos fazer uma função de cumprimentar, supondo que seu nome é `X` e irá cumprimentar uma pessoa de nome `Y`, a função para isto seria:

```javascript
function cumprimentar(X, Y) {
  console.log(`Olá, eu sou ${X}, prazer em lhe conhecer ${Y}`)
}

cumprimentar('Fagner', 'Fulano de Tal')
```
Resultado:
```
=> Olá, eu sou Fagner, prazer em lhe conhecer Fulano de Tal
```

> Note que mesmo no escopo da função, existe uma **outra** função, podemos ver isto por conta das `()` aparecendo após o nome `log`, então sim, uma função pode executar outras funções dentro do seu próprio escopo!

"Mas ainda não entendi, quais as vantagens de de utilizar funções?"

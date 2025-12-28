# Guia de Introdução à Linguagem Lua para Crianças

## Lendo do Teclado

Use `io.read()` para ler entrada do usuário.

### Básico

```lua
print("Digite seu nome:")
local nome = io.read()
print("Olá, " .. nome)
```

- `io.read()` lê uma linha e retorna como **string**. Sempre retorna uma string, não um número ou booleano.

### Lendo Números

```lua
print("Qual sua idade:")
local idade = io.read()
print("Você tem: " .. idade .. ' anos')
```

### Exercícios

> Quando dizemos "Imprima", significa usar `print()` para mostrar o valor na tela.

1. Pergunte nome e imprima "Oi, [nome]".

2. Pergunte idade e imprima "Você tem [idade] anos".
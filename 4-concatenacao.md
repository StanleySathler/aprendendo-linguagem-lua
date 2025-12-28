# Guia de Introdução à Linguagem Lua para Crianças

## (4) Concatenação

Junte strings com `..`

### Exemplos

```lua
local nome = "Oliver" -- Variável já é do tipo String
local saudacao = "Olá, " .. nome .. "!"

print(saudacao)  -- "Olá, Oliver!"
```

Perceba como `..` junta as strings.

```lua
local idade = 8 -- Variável é do tipo Numero
local frase = "Eu tenho " .. idade .. " anos."

print(frase)  -- "Eu tenho 8 anos."
```

### Exercícios

> Quando dizemos "Imprima", significa usar `print()` para mostrar o valor na tela.

1. Junte "Meu nome é " com uma variável `nome`. Imprima.

2. Junte "Eu tenho " com uma variável `idade` e " anos". Imprima.

3. Junte "Gosto de " com uma variável `comida`. Imprima.
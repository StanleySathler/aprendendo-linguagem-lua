# Guia de Introdução à Linguagem Lua para Crianças

## (5) Condicionais

Use `if`, `then`, `else` para decisões.

### Básico

```lua
local idade = 12

if idade >= 10 then
    print("Pode brincar")
else
    print("Não pode")
end
```

- `if condição then`: Se verdadeiro, executa.
- `else`: Senão.
- `end`: Fecha.

### Comparações

- `==`: Igual
- `>`: Maior
- `<`: Menor
- `>=`: Maior ou igual
- `<=`: Menor ou igual
- `~=` : Diferente

### Exemplos

**Com elseif:**

```lua
local nota = 8

if nota >= 9 then
    print("Excelente")
elseif nota >= 7 then
    print("Bom")
else
    print("Precisa melhorar")
end
```

### Exercícios

1. Se idade >= 18, imprima "Adulto", senão "Jovem".

2. Se nome == "Ana", imprima "Olá Ana", senão "Olá estranho".

3. Se número > 10, imprima "Grande", senão "Pequeno".
# Guia de Introdução à Linguagem Lua para Crianças

## Laços de Repetição

Use laços para repetir ações.

### For

Repete um número fixo de vezes.

```lua
for i = 1, 5 do -- Para 1 até 5, faça:
    print("Número: " .. i)
end
-- Imprime 1 a 5
```

### While

Repete enquanto condição for true.

```lua
local i = 1
while i <= 5 do
    print("Número: " .. i)
    i = i + 1
end
-- Imprime 1 a 5
```

### Exemplos

**Contar até 10:**

```lua
for i = 1, 10 do
    print(i)
end
```

**Perguntar até dizer "sair":**

```lua
local resposta = ""
while resposta ~= "sair" do
    print("Digite algo (ou 'sair'):")
    resposta = io.read()
    print("Você disse: " .. resposta)
end
```

### Exercícios

1. Use for para imprimir "Olá" 3 vezes.

2. Use while para somar números até 10.

3. Crie um loop que leia nomes até digitar "fim".
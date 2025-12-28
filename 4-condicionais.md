# Guia de Introdução à Linguagem Lua para Crianças

## (4) Condicionais

- if = se
- then = então
- else = senão

### If (Se) .. then (Então)

Na programação, é comum você só executar um pedaço de código se uma condição for verdadeira.

Por exemplo - Em um jogo, se o jogador tiver 100 moedas, ele pode comprar uma espada.

Outro exemplo - Se o jogador digitar a senha certa, ele pode entrar na conta.

Use `if` para decisões.

```lua
local idade = 18
if idade >= 18 then -- Se idade é maior ou igual a 18
    print("Você é adulto")
end
```

Tudo que estiver entre `if` e `end` só executa se a condição for verdadeira.

### Else (Senão)

Você também pode usar `else` para fazer algo quando a condição for falsa.

Por exemplo - Se o jogador tiver 100 moedas, ele pode comprar uma espada, senão, mostra uma mensagem dizendo "não há moedas suficientes".

```lua
local moedas = 50
if moedas >= 100 then -- Se moedas é maior ou igual a 100
    print("Você comprou uma espada!")
else
    print("Não há moedas suficientes. Você precisa de 100 moedas, mas só tem " .. tostring(moedas) .. " moedas")
end
```

### Comparações

- `a == b` : Se a é igual a b
- `a > b` : Se a é maior que b
- `a < b` : Se a é menor que b
- `a >= b` : Se a é maior ou igual a b
- `a <= b` : Se a é menor ou igual a b
- `a ~= b` : Se a é diferente de b

### Operadores lógicos

- `nome == 'Oliver' or nome == 'Luna'` : Se o nome é Oliver ou Luna
- `nome == 'Oliver' and senha == '1234'` : Se o nome é Oliver e a senha é 1234

### Exemplos

Checa se o usuário e senha estão corretos:

```lua
print("Seu nome:")
local nome = io.read()

print("Sua senha:")
local senha = io.read()

if nome == "Oliver" and senha == "1234" then
    print("Acesso permitido")
else
    print("Acesso negado")
end
```

### Exercícios

1. Crie um programa que pergunte a idade do usuário e diga se ele é menor de idade (menos de 18 anos) ou adulto (igual ou maior que 18 anos).

2. Crie um programa que checa se o jogador tem moedas suficientes para comprar um item que custa 150 moedas. Se tiver, mostre "Compra realizada!", senão, mostre um erro.
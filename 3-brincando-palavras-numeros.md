# Guia de Introdução à Linguagem Lua para Crianças

## (3) Brincando com Palavras e Números

Olá, pequeno programador! Agora que você já sabe o que é programar e como preparar o Lua no seu computador, vamos começar a brincar de verdade. Imagine que o computador é como uma caixa de brinquedos gigante, e você pode guardar coisas nela. Essas "coisas" são chamadas de **variáveis**. Elas podem ser palavras (como nomes de amigos), números (como quantos doces você tem) ou até respostas de sim/não.

Vamos aprender passo a passo, com exemplos divertidos. Abra o seu editor de código e teste tudo!

### Variáveis: Caixas para Guardar Segredos

Uma variável é como uma caixa onde você guarda um valor. Você dá um nome à caixa e coloca algo dentro dela. Em Lua, usamos o sinal `=` para "guardar" o valor. Para variáveis locais (que só existem no seu pedaço de código), é bom usar a palavra `local` no começo. Sem ela, a variável fica global (visível em todo o programa).

**Exemplo 1: Guardando um nome (palavra)**  
```lua
local meuNome = "Oliver"
print(meuNome)  -- Isso mostra "Oliver" na tela
```

- `local meuNome` cria uma caixa local chamada `meuNome`.  
- `"Oliver"` é o que está dentro (uma palavra, chamada de *string*).  
- `print()` é como dizer ao computador: "Mostre isso na tela!"

**Exemplo 2: Guardando um número**  
```lua
local meusDoces = 10
print(meusDoces)  -- Mostra 10
```

- `local meusDoces` guarda o número 10 localmente.  
- Números não precisam de aspas, só palavras!

**Dica divertida:** Tente mudar o valor e veja o que acontece. Por exemplo, mude `meusDoces = 10` para `meusDoces = 20` e rode o código de novo. É como trocar o brinquedo na caixa!

### Tipos de Dados: Texto, Números e Verdadeiros/Falsos

Em Lua, os valores têm "tipos", como categorias de brinquedos. Os principais são:

- **Texto (string):** Palavras ou frases, sempre entre aspas. Exemplo: `"Olá, mundo!"`  
- **Números (number):** Para contar ou calcular. Exemplo: `5` ou `3.14`  
- **Verdadeiro/Falso (boolean):** Como sim ou não. Exemplo: `true` (verdadeiro) ou `false` (falso)

**Exemplo 3: Contando doces com tipos diferentes**  
```lua
local nomeDoDoce = "Chocolate"  -- Texto
local quantidade = 5            -- Número
local temMais = true            -- Verdadeiro/Falso

print("Eu tenho " .. quantidade .. " doces de " .. nomeDoDoce)
print("Tem mais? " .. tostring(temMais))  -- Mostra "true"
```

- O `..` junta textos e números, como colar pedaços de papel.  
- `tostring()` transforma `true` em texto para mostrar.

### Lendo do Teclado: Fazendo o Computador Perguntar

Em Lua, você pode fazer o computador perguntar algo e guardar a resposta em uma variável. Usamos `io.read()` para ler do teclado.

**Exemplo 4: Perguntando o nome**  
```lua
print("Qual é o seu nome?")
local nome = io.read()
print("Olá, " .. nome .. "! Que nome legal!")
```

- `io.read()` espera você digitar e apertar Enter.  
- O que você digita vai para a variável `nome`.

**Exemplo 5: Perguntando um número**  
```lua
print("Quantos anos você tem?")
local idadeTexto = io.read()
local idade = tonumber(idadeTexto)  -- Transforma texto em número
print("Você tem " .. idade .. " anos!")
```

- `tonumber()` muda texto para número, porque `io.read()` sempre lê como texto.

**Dica:** Teste digitando coisas diferentes. É como conversar com o computador!

**Exercício para você:**  
1. Crie uma variável com o seu nome e mostre na tela.  
2. Guarde quantos anos você tem e imprima uma frase como "Eu tenho X anos!".  
3. Faça uma variável `gostoDePizza = true` e mostre se você gosta ou não.  
4. Use `io.read()` para perguntar o nome de um amigo e dizer "Oi, [nome]!".  
5. Pergunte quantos doces alguém tem e mostre uma mensagem legal.

Se der erro, não se preocupe! É normal no começo. Verifique se as aspas estão certas e se não esqueceu o `=`.

### Próximos Passos

Parabéns! Você aprendeu a guardar e mostrar palavras e números. Na próxima seção, vamos aprender a tomar decisões, como escolher qual brinquedo pegar. Pratique esses exemplos e me diga se quiser ajuda!
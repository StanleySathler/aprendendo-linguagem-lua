# Guia de Introdução à Linguagem Lua para Crianças

## (3) Brincando com Palavras e Números

Olá, pequeno programador! Agora que você já sabe o que é programar e como preparar o Lua no seu computador, vamos começar a brincar de verdade. Imagine que o computador é como uma caixa de brinquedos gigante, e você pode guardar coisas nela. Essas "coisas" são chamadas de **variáveis**. Elas podem ser palavras (como nomes de amigos), números (como quantos doces você tem) ou até respostas de sim/não.

Vamos aprender passo a passo, com exemplos divertidos. Abra o seu editor de código e teste tudo!

### Variáveis: Caixas para Guardar Segredos

Uma variável é como uma caixa onde você guarda um valor. Você dá um nome à caixa e coloca algo dentro dela. Em Lua, usamos o sinal `=` para "guardar" o valor.

**Exemplo 1: Guardando um nome (palavra)**  
```lua
meuNome = "João"
print(meuNome)  -- Isso mostra "João" na tela
```

- `meuNome` é o nome da caixa (variável).  
- `"João"` é o que está dentro (uma palavra, chamada de *string*).  
- `print()` é como dizer ao computador: "Mostre isso na tela!"

**Exemplo 2: Guardando um número**  
```lua
meusDoces = 10
print(meusDoces)  -- Mostra 10
```

- `meusDoces` guarda o número 10.  
- Números não precisam de aspas, só palavras!

**Dica divertida:** Tente mudar o valor e veja o que acontece. Por exemplo, mude `meusDoces = 10` para `meusDoces = 20` e rode o código de novo. É como trocar o brinquedo na caixa!

### Tipos de Dados: Texto, Números e Verdadeiros/Falsos

Em Lua, os valores têm "tipos", como categorias de brinquedos. Os principais são:

- **Texto (string):** Palavras ou frases, sempre entre aspas. Exemplo: `"Olá, mundo!"`  
- **Números (number):** Para contar ou calcular. Exemplo: `5` ou `3.14`  
- **Verdadeiro/Falso (boolean):** Como sim ou não. Exemplo: `true` (verdadeiro) ou `false` (falso)

**Exemplo 3: Contando doces com tipos diferentes**  
```lua
nomeDoDoce = "Chocolate"  -- Texto
quantidade = 5            -- Número
temMais = true            -- Verdadeiro/Falso

print("Eu tenho " .. quantidade .. " doces de " .. nomeDoDoce)
print("Tem mais? " .. tostring(temMais))  -- Mostra "true"
```

- O `..` junta textos e números, como colar pedaços de papel.  
- `tostring()` transforma `true` em texto para mostrar.

**Exercício para você:**  
1. Crie uma variável com o seu nome e mostre na tela.  
2. Guarde quantos anos você tem e imprima uma frase como "Eu tenho X anos!".  
3. Faça uma variável `gostoDePizza = true` e mostre se você gosta ou não.

Se der erro, não se preocupe! É normal no começo. Verifique se as aspas estão certas e se não esqueceu o `=`.

### Próximos Passos

Parabéns! Você aprendeu a guardar e mostrar palavras e números. Na próxima seção, vamos aprender a tomar decisões, como escolher qual brinquedo pegar. Pratique esses exemplos e me diga se quiser ajuda!
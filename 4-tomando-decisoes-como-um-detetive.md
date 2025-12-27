# Guia de Introdução à Linguagem Lua para Crianças

## (4) Tomando Decisões como um Detetive

Olá, detetive em treinamento! Agora que você sabe guardar palavras e números em variáveis, vamos aprender a tomar decisões. Imagine que você é um detetive resolvendo um mistério: "Se isso acontecer, então faça aquilo. Senão, faça outra coisa." Em Lua, usamos `if`, `then` e `else` para isso. Também comparamos coisas com sinais como `==` (igual), `>` (maior) e `<` (menor).

Vamos ver exemplos divertidos. Lembre-se de testar o código!

### Condições: Se... Então... Senão

Uma condição é como uma pergunta: "Será que...?" Se a resposta for sim, faz uma coisa. Se não, faz outra.

**Exemplo 1: Verificando se você é grande o suficiente para um brinquedo**  
```lua
local minhaIdade = 12

if minhaIdade >= 10 then
    print("Você pode brincar com o brinquedo grande!")
else
    print("Melhor escolher um brinquedo pequeno.")
end
```

- `if minhaIdade >= 10 then` pergunta: "Idade é maior ou igual a 10?"  
- Se sim, mostra a primeira mensagem.  
- `else` é o "senão": se não, mostra a segunda.  
- `end` fecha a condição.

**Dica:** Mude `minhaIdade = 12` para `minhaIdade = 8` e veja o que acontece. É como escolher caminhos em uma aventura!

### Comparações: Maior, Menor, Igual

Usamos comparações para decidir. Elas sempre dão `true` (verdadeiro) ou `false` (falso).

- `==` : Igual (ex: `5 == 5` é true)  
- `>` : Maior que (ex: `10 > 5` é true)  
- `<` : Menor que (ex: `3 < 7` é true)  
- `>=` : Maior ou igual  
- `<=` : Menor ou igual  
- `~=` : Diferente (ex: `5 ~= 3` é true)

**Exemplo 2: Jogo de adivinhação com números**  
```lua
local numeroSecreto = 7
local meuPalpite = 5

if meuPalpite == numeroSecreto then
    print("Acertou! Você é um gênio!")
elseif meuPalpite > numeroSecreto then
    print("Muito alto! Tente um número menor.")
else
    print("Muito baixo! Tente um número maior.")
end
```

- `if` verifica se é igual.  
- `elseif` é outro "se" se o primeiro não for.  
- `else` para o resto.  

**Exemplo 3: Decidindo com palavras**  
```lua
local meuAnimalFavorito = "gato"

if meuAnimalFavorito == "cachorro" then
    print("Au au! Vamos brincar de buscar a bolinha?")
elseif meuAnimalFavorito == "gato" then
    print("Miau! Prefiro dormir no sol.")
else
    print("Que animal legal! Me conte mais sobre ele.")
end
```

- Compara palavras com `==`. Elas precisam ser iguais, incluindo maiúsculas/minúsculas.

**Exercício para você:**  
1. Crie uma variável com sua idade e use `if` para dizer se você gosta de doces ou não (invente uma regra!).  
2. Faça um jogo: guarde um número secreto e compare com um palpite, mostrando dicas.  
3. Experimente `~=` : Se o animal não for "gato", diga "Talvez seja um cachorro?".

Se der erro, confira os sinais: `==` tem dois iguais, e não esqueça o `end`!

### Próximos Passos

Incrível! Agora você toma decisões como um detetive. Na próxima seção, vamos repetir ações como um robô. Pratique e me chame se precisar de ajuda!
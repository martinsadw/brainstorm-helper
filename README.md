# brainstorm helper.
Pequeno prompt do Gemini para ajudar a fazer brainstorm de ideias

Link para o notebook:  
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/martinsadw/brainstorm-helper/blob/main/brainstorm_helper.ipynb)

# 1. Instruções de uso

As interações com o modelo funcionam em três etapas: **Elaboração**, **Refinamento** e **Exploração** de ideias.  
É possível digitar "SAIR" (sem aspas, em letras maiúsculas) a qualquer momento para encerrar a interação.

## 1.1. Elaboração de ideias

Na primeira etapa, tudo o que for enviado para o modelo será adicionado à lista de ideias. É possivel pedir para o modelo remover uma ideia caso tenha sido adicionada incorretamente. Quando terminar de adicionar as ideias diga "Finalizar" para processeguir para a próxima etapa.

## 1.2. Refinamento de ideias

Após finalizar a primeira etapa, o modelo irá sugerir novas ideias para expandir as ideias sugeridas originalmente. Em seguida o modelo irá resumir a lista em um conjunto reduzido de ideias. Ideias que sejam muito similares serão agregadas em um conjunto de tópicos mais amplos. O modelo seguirá automaticamente para a próxima etapa.

## 1.3. Exploração de ideias

Por fim, o modelo se disponibilizará a responder perguntas relacionadas as ideias propostas. Pode se pedir mais detalhes sobre algum dos itens, estimativas de custo para a execução das ideias, solicitar que o modelo crie um esboço de implementação das tarefas, entre outras ideias. Sua criatividade é o limite aqui.

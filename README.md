<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="/assets/dark_480.png">
    <source media="(prefers-color-scheme: light)" srcset="/assets/light_480.png">
    <img alt="Shows an illustrated sun in light mode and a moon with stars in dark mode." src="/assets/light_480.png">
  </picture>
</p>

Pequeno prompt do Gemini para ajudar a fazer brainstorm de ideias

**Link para o notebook no Google Colab:**  
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/martinsadw/brainstorm-helper/blob/main/brainstorm_helper.ipynb)

# 1. Preparação

- Crie uma Chave de API [(link)](https://aistudio.google.com/app/apikey);
- Adicione a chave à lista de secrets do Google Colab com o nome `GOOGLE_API_KEY`;
- Habilite o acesso da chave pelo notebook;
- Clique em `Ambiente de execução > Executar tudo` ou aperte `Ctrl + F9` e espera até o modelo ser instânciado.

# 2. Instruções de uso

As interações com o modelo funcionam em três etapas: **Elaboração**, **Refinamento** e **Exploração** de ideias.  
É possível digitar "SAIR" (sem aspas, em letras maiúsculas) a qualquer momento para encerrar a interação.

## 2.1. Elaboração de ideias

Na primeira etapa, tudo o que for enviado para o modelo será adicionado à lista de ideias. É possivel pedir para o modelo remover uma ideia caso tenha sido adicionada incorretamente. Quando terminar de adicionar as ideias diga "Finalizar" para processeguir para a próxima etapa.

## 2.2. Refinamento de ideias

Após finalizar a primeira etapa, o modelo irá sugerir novas ideias para expandir as ideias sugeridas originalmente. Em seguida o modelo irá resumir a lista em um conjunto reduzido de ideias. Ideias que sejam muito similares serão agregadas em um conjunto de tópicos mais amplos. O modelo seguirá automaticamente para a próxima etapa.

## 2.3. Exploração de ideias

Por fim, o modelo se disponibilizará a responder perguntas relacionadas as ideias propostas. Pode se pedir mais detalhes sobre algum dos itens, estimativas de custo para a execução das ideias, solicitar que o modelo crie um esboço de implementação das tarefas, entre outras ideias. Sua criatividade é o limite aqui.

# 3. Exemplo

- Criar um modelo para auxiliar em um brainstorming
- Criar um site para organizar tarefas
- Permitir adicionar membros e atribuir esse membros às tarefas
- Permitir criar grupos de trabalho
- Criar um modelo para organizar reuniões

![Uso no Colab](/assets/colab.png)

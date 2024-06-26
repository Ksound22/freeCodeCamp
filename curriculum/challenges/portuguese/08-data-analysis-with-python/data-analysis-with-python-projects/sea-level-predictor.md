---
id: 5e4f5c4b570f7e3a4949899f
title: Previsor de nível do mar
challengeType: 10
forumTopicId: 462370
dashedName: sea-level-predictor
---

# --description--

Você <a href="https://gitpod.io/?autostart=true#https://github.com/freeCodeCamp/boilerplate-sea-level-predictor/" target="_blank" rel="noopener noreferrer nofollow">trabalhará nesse projeto com o nosso código inicial do Gitpod </a>.

Ainda estamos desenvolvendo a parte instrucional interativa do currículo Python. Por enquanto, aqui estão alguns vídeos no canal do freeCodeCamp.org do YouTube que ensinarão tudo o que você precisa saber para completar este projeto:

- <a href="https://www.freecodecamp.org/news/python-for-everybody/" target="_blank" rel="noopener noreferrer nofollow">Curso de Python em vídeo para todos</a> (14 horas)

- <a href="https://www.freecodecamp.org/news/how-to-analyze-data-with-python-pandas/" target="_blank" rel="noopener noreferrer nofollow">Como analisar dados em Python com o Pandas</a> (10 horas)

# --instructions--

Você analisará um dataset da mudança média do nível do mar global desde 1880. Você utilizará os dados para prever a mudança do nível do mar até ao ano de 2050.

Use os dados para completar as seguintes tarefas:

- Use o Pandas para importar os dados de `epa-sea-level.csv`.
- Use a matplotlib para criar um diagrama de dispersão usando a coluna `Year` como eixo x e a coluna `CSIRO Adjusted Sea Level` (Nível do mar ajustado) como o eixo y.
- Use a função `linregress` do `scipy.stats` para obter o coeficiente angular e o ponto de interceptação da linha de y do melhor ajuste. Trace a linha de melhor ajuste na parte superior do diagrama de dispersão. Faça a linha passar pelo ano 2050 para prever o aumento do nível do mar em 2050.
- Trace uma nova linha do melhor ajuste utilizando apenas os dados do ano 2000 ao longo do último ano no dataset. Faça com que a linha passe também pelo ano 2050 para prever o aumento do nível do mar em 2050 se a taxa de crescimento continuar como está desde o ano 2000.
- O rótulo de x deve ser `Year` e o rótulo de y deve ser `Sea Level (inches)` (Nível do mar, em polegadas), e o título deve ser `Rise in Sea Level` (Aumento do nível do mar).

O boilerplate também inclui comandos para salvar e retornar a imagem.

## Desenvolvimento

Escreva seu código em `sea_level_predictor.py`. Para o desenvolvimento, você pode usar `main.py` para testar o seu código.

## Testes

Os testes unitários para esse projeto estão em `test_module.py`. Importamos os testes de `test_module.py` em `main.py` para a sua conveniência.

## Envio

Copie o URL do seu projeto e envie-o para o freeCodeCamp.

## Fonte dos dados

<a href="https://datahub.io/core/sea-level-rise" target="_blank" rel="noopener noreferrer nofollow">Global Average Absolute Sea Level Change</a>, 1880-2014 da Agência de Proteção Ambiental dos EUA, usando dados do CSIRO, 2015; NOAA, 2015.


# --hints--

Ele deve passar em todos os testes do Python.

```js

```

# --solutions--

```py
  # Python challenges don't need solutions,
  # because they would need to be tested against a full working project.
  # Please check our contributing guidelines to learn more.
```

# Random_forest_qualidade_vinho_P9
Prevendo a qualidade do vinho
## Objetivo do projeto
O objetivo desse projeto é fazer uma previsão da variável Quality (fala sobre a pontuação do vinho baseada em dados sensoriais), com base em outras variáveis presentes no dataset.

## Dados do Dataset
**Vamos conhecer nossa base:**

- Fixed Acidity: Acidez fixa do vinho.

- Volatile Acidity: Acidez volátil do vinho.

- Citric Acid: Quantidade de ácido cítrico no vinho.

- Residual Sugar: Açúcar residual presente no vinho.

- Chlorides: Nível de cloretos no vinho.

- Free Sulfur Dioxide: Dióxido de enxofre livre no vinho.

- Total Sulfur Dioxide: Quantidade total de dióxido de enxofre no vinho.

- Density: Densidade do vinho.

- pH: Nível de pH do vinho.

- Sulphates: Quantidade de sulfatos no vinho.

- Alcohol: Teor alcoólico do vinho.

- Quality: Pontuação do vinho baseada em dados sensoriais, variando de 0 a 10. (TARGET)

## Etapas do projeto

1. Carregamento e pré-processamento dos dados.
2. Análise exploratória dos dados (compreensão da distribuição, verificação de outliers, e correlação)
3. Separação de dados em treino e teste.
4. Modelagem com Random Forest
5. Avaliação das métricas
6. Melhoramento com Hiperparâmetros com RandomizedSeachCV
7. Comparação entre modelos.


## Conclusão
- O modelo apresentou dificuldades em generalizar classes minoritárias, o que se deve ao forte desbalanceamento do dataset e à baixa quantidade de amostras disponíveis para determinadas categorias. Portanto a quantidade de dados disponibilizados influenciam diretamente na capacidade do modelo em suas previsões.

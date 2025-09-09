# Ciencia-de-Dados-e-Inteligencia-Artificial

Projeto: desenvolvimento de um processo de ciência de dados no Orange Data Mining usando o Dataset Fetal Health:
* Exploração dos dados;
* Escolha dos algoritmos de aprendizado para a modelagem (pelo menos 3 algoritmos);
* Preparação dos dados de acordo com as características dos algoritmos de aprendizado Escolhidos
* Execução dos experimentos de aprendizado e coleta das métricas;
-------------------------------------------------------------------------------

Este conjunto de dados contém registros de exames de cardiotocograma (CTG), utilizados para monitorar a saúde fetal durante a gestação. Cada linha representam um exame com 21 atributos clinícos e um atributo alvo (fetal_health) que classifica o estado do feto como normal, suspeito ou patológico. O objetivo é prever a saúde fetal com base em sinais fisiológicos extraídos dos exames.
A variável fetal_health é a classificação da condição de saúde do feto, baseada em sinais extraídos da cardiotocografia (CTG). Ela é uma variável categórica ordinal, com três possíveis valores:
Valor	Significado:
1	= Saúde fetal normal
2	= Saúde fetal suspeita
3	= Saúde fetal patológica (indica risco ou sofrimento fetal)

--------------------------------------------------------------------------------

Três algoritmos supervisionados foram utilizados para a modelagem:

k-Nearest Neighbors (kNN) – id 9: Algoritmo baseado em distância, ideal para detectar padrões locais. Sensível à escala dos dados, por isso se beneficia da normalização.

Logistic Regression – id 10: Modelo estatístico linear, eficaz para problemas de classificação binária e multiclasse. Oferece boa interpretabilidade e desempenho consistente.

Random Forest – id 11: Algoritmo de ensemble baseado em árvores de decisão. Robusto contra overfitting e eficaz em conjuntos de dados com variáveis heterogêneas.

Cada modelo foi conectado ao widget Test and Score, permitindo uma comparação direta de desempenho. Os resultados foram posteriormente analisados nos widgets Evaluation Results, Confusion Matrix, ROC Analysis, Box Plot, Heat Map e Rank, proporcionando uma avaliação abrangente e visualmente rica.

<img width="1620" height="835" alt="image" src="https://github.com/user-attachments/assets/3416185d-44b8-420a-aa38-b69c974e511e" />

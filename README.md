# Projeto: Transfer Learning para Classificação de Imagens

Este projeto utiliza a técnica de Transfer Learning para otimizar o treinamento de um modelo de classificação de imagens, destacando sua eficiência em cenários com recursos computacionais limitados.

Do 'Kaggle Cats and Dogs Dataset' (https://www.microsoft.com/en-us/download/details.aspx?id=54765), serão selecionadas automaticamente 1.000 imagens de gatos e 1.000 de cachorros, totalizando 2.000 das 25.000 imagens disponíveis. Inicialmente, o modelo será treinado do zero com essas imagens para estabelecer uma baseline de desempenho.

Em seguida, com base no 'Notebook de Transfer Learning de Kyle Mathewson' (https://colab.research.google.com/github/kylemath/ml4a-guides/blob/master/notebooks/transfer-learning.ipynb), aplicaremos a técnica de Transfer Learning utilizando o modelo pré-treinado VGG16 (vencedor do ImageNet Challenge em 2014), ajustando-o com o mesmo conjunto de dados.

Os resultados obtidos demonstrarão que o Transfer Learning pode alcançar maior acurácia em menos tempo, evidenciando sua relevância para problemas práticos e otimizando o uso de recursos computacionais.

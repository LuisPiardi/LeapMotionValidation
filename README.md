Este repositorio contem a versao 3.2.1 do LeapDevelopeKit.


Para realizar a validacao, a ideia è realizar 12 experimentos, representando apenas um gesto por vez e salvar estes dados em um .csv para avaliar a precisao do sistema
com movimentos aleatòrios e posicoes aleatorias para o mesmo gesto

Neste repositorio, a pasta /Application contem:
- scripts python para utilizar o sdk e obter gestos e posicao da mao com o Leap Motion
- o script "GestureClasification.py" obtèm 2000 amostras de frames que contèm maos e salva num arquivo .csv
- o script "DataAnalyse.py" realiza a leitura e quantifica a precisao de cada gesto.

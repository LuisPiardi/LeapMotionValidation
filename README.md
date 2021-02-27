Este repo contém a versão 3.2.1 do LeapDevelopeKit e Python versão 2.7.


Para realizar a validação, a ideia é realizar 12 experimentos, representando apenas um gesto por vez e salvar estes dados em um .csv para avaliar a precisão do sistema
com movimentos aleatórios e posições aleatórias para o mesmo gesto

Neste repositório, a pasta /Aplicativo contém:
- Scripts python para utilizar o SDK e obter gestos e posição da mão com o Leap Motion
- O script "GestureClasification.py" obtém 2000 amostras de frames que contém mãos e salva num arquivo .csv
- O script "DataAnalyse.py" realiza a leitura e quantifica a precisão de cada gesto.


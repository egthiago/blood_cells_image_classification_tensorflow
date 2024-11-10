# Classificação de Células Sanguíneas com TensorFlow

Este projeto utiliza deep learning para classificar imagens de células nucleadas do sangue periférico em diferentes categorias (neutrófilos, eosinófilos, basófilos, linfócitos, células imaturas, eritroblastos e plaquetas) utilizando a biblioteca Tensorflow. O modelo é treinado e avaliado com um conunto de imagens baixados diretamento do Kaggle. 
Inicialmente, o dataset foi dividido em grupos de treniamento e validação (20% do total de imagens do dataset). Inicialmente, foi desenvolvido um modelo de Perceptron de Múltiplas Camadas, que foi aprimorado com camadas convolucionais e pooling para aumentar a precisão. Foram realizados testes também com o número de épocas de treinamento, de forma a otimizar a acurácia e perda. 
Uma função (plota_resultados) para exibição dos gráficos de acurácia e perda foi desenvolvida para avaliar cada um dos ajustes no modelo. 
Para finalizar, é possível carregar uma nova imagem a partir de uma url do Google Drive para testar o modelo. O teste exibe um gráfico de probabilidades da categoria esperada. 

O projeto foi desenvolvido utilizando o Google Colab com execução em GPU. 

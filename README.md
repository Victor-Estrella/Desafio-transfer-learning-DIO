# Projeto Transfer Learning com Deep Learning no Google Colab - DIO
### Descrição
Este projeto tem como objetivo aplicar o método de Transfer Learning utilizando uma rede de Deep Learning pré-treinada (VGG16) na linguagem Python, dentro do ambiente Google Colab.

O projeto originalmente utiliza o dataset Cats vs Dogs (gatos e cachorros) para demonstrar a técnica, mas pode ser facilmente adaptado para qualquer outro conjunto de imagens, como fotos pessoais, animais de estimação, objetos ou qualquer outra categoria que você queira classificar.

Você pode usar:
- O dataset de gatos e cachorros fornecido pelo TensorFlow Datasets,
- Ou uma base de dados própria que você tenha criado, inclusive aquela gerada em projetos anteriores.

### Funcionalidades
- Carregamento automático do dataset (Cats vs Dogs via TFDS).
- Pré-processamento das imagens para o formato aceito pelo modelo VGG16.
- Utilização do modelo VGG16 pré-treinado como extrator de características (camadas convolucionais congeladas).
- Criação e treinamento de camadas densas personalizadas para a classificação das suas classes.
- Avaliação do modelo com dados de validação e teste.
- Visualização dos gráficos de loss (perda) e accuracy (acurácia) durante o treinamento.

### Como usar
1. Abra o notebook no Google Colab.
2. Execute todas as células para baixar os dados, montar o modelo e treinar.
3. Para usar seu próprio dataset:
    - Organize suas imagens em pastas separadas por classe.
    - Faça o pré-processamento adaptado para seu conjunto (tamanho, rótulos).
    - Ajuste o número de classes na definição do modelo.
4. Treine o modelo com seus dados.
5. Avalie a performance e visualize as métricas.

### Requisitos
- Python 3.x
- TensorFlow 2.x
- TensorFlow Datasets (`tensorflow-datasets`)
- Matplotlib

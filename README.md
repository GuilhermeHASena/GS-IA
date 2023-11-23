# GS-IA
Classificação de Imagens Oftalmológicas usando Redes Neurais Convolucionais (CNN)
Este código implementa um sistema de classificação de imagens oftalmológicas em quatro categorias: "normal", "glaucoma", "diabete retinopática" e "catarata".

1. Importando as bibliotecas
Este bloco de código importa as bibliotecas necessárias para a implementação, incluindo matplotlib, scikit-learn, OpenCV, PIL, NumPy, e Pandas.

2. Descomprimindo a pasta do dataset
Descomprime a pasta do dataset (dataset.zip) que contém as imagens oftalmológicas.

3. Listando o conteúdo do dataset
Exibe a lista de diretórios presentes na pasta do dataset.

4. Plotando a quantidade de imagens que serão usadas
Calcula e exibe a quantidade de imagens disponíveis em cada diretório, usando um gráfico de barras.

5. Especificando as pastas a serem analisadas
Define os caminhos para as pastas que contêm as imagens classificadas como "normal", "glaucoma", "diabete retinopática" e "catarata".

6. Criando os dicionários de nomes e imagens para os testes
Cria dicionários associando os rótulos (nomes) às listas de imagens correspondentes.

7. Plotando uma imagem
Demonstra como abrir e exibir uma imagem do diretório "normal".

8. Formatando as imagens
Redimensiona e normaliza as imagens, convertendo-as em arrays.

9. Criando os conjuntos de treino e teste e construindo o modelo
Divide as imagens em conjuntos de treino e teste. Em seguida, constrói um modelo de rede neural, com data augmentation para melhorar a generalização do modelo.

10. Geração de testes e visualização dos resultados
Treina o modelo, avalia o desempenho no conjunto de teste e gera previsões para as primeiras 10 imagens do conjunto de teste, exibindo as imagens reais e as previsões do modelo.
Esse código fornece uma estrutura básica para classificação de imagens usando CNNs e pode ser personalizado para outros conjuntos de dados ou problemas de classificação de imagem.

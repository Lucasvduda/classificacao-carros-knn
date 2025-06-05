Título do Projeto: Classificação de Carros com KNN

Descrição:
Este projeto implementa um modelo de aprendizado de máquina utilizando o algoritmo KNN (k-nearest neighbors)
para classificar veículos com base em sua eficiência de combustível (milhas por galão) e potência do motor.
A classificação é feita para determinar o número de cilindros do carro, utilizando métricas de desempenho como acurácia, precisão, recall e F1-Score.

O objetivo do projeto é demonstrar o uso prático de KNN, explorando técnicas de manipulação de dados e avaliação de modelos.

O que o projeto faz:
Carrega os dados do dataset mt_cars.csv contendo informações sobre carros.

Define variáveis de entrada (X) e saída (y) para o modelo:

Entrada: mpg (milhas por galão) e hp (potência do motor).

Saída: cyl (número de cilindros).

Treina o modelo KNN utilizando 3 vizinhos mais próximos.

Faz previsões tanto para os dados originais quanto para novos dados.

Avalia o desempenho do modelo com métricas e matriz de confusão.

Analisa as distâncias e os vizinhos mais próximos de um novo ponto previsto.

Tecnologias Utilizadas
Linguagem: Python

Bibliotecas:

Pandas: Manipulação de dados tabulares.

NumPy: Operações matemáticas e arrays.

Scikit-learn: Implementação do algoritmo KNN e métricas de avaliação.

Métricas de Desempenho:

accuracy_score: Mede a porcentagem de previsões corretas.

precision_score: Mede a precisão para cada classe.

recall_score: Mede a taxa de identificação de positivos verdadeiros.

f1_score: Combina precisão e recall.

confusion_matrix: Mostra uma matriz de comparação entre previsões e valores reais.

Estrutura do Projeto
mt_cars.csv: Dataset usado para treinamento e teste.

main.py: Script principal contendo o código do projeto.

README.md: Documentação detalhada sobre o projeto.

Fluxo do Projeto
Carregar o dataset: Os dados de carros são carregados do arquivo CSV.

Pré-processamento: As colunas necessárias são extraídas e transformadas em arrays NumPy.

Treinamento do modelo: Um modelo KNN com 3 vizinhos é treinado usando as variáveis de entrada e saída.

Avaliação do modelo: O modelo é avaliado com métricas como acurácia, precisão, recall, F1 e matriz de confusão.

Previsões: O modelo faz previsões para os dados do dataset e para novos pontos fornecidos manualmente.

Análise dos vizinhos: O modelo identifica os vizinhos mais próximos e suas distâncias em relação a novos dados.

Como Executar o Projeto
Clone o repositório:
git clone https://github.com/seu_usuario/classificacao-carros-knn.git

Instale as dependências:
pip install -r requirements.txt

Coloque o arquivo mt_cars.csv na pasta principal do projeto.

Execute o script:
python main.py


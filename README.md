# Projeto de Clusterização de Dados Sócio-Econômicos

Este projeto tem como objetivo realizar uma análise de clusterização em um conjunto de dados sócio-econômicos de diferentes países. Utilizamos diversos algoritmos de clusterização, incluindo K-Médias, Clusterização Hierárquica e DBScan, para identificar grupos de países com características semelhantes.

## Objetivos do Projeto

1. **Análise Exploratória dos Dados**:
   - Carregar e explorar o conjunto de dados.
   - Verificar a presença de valores ausentes e duplicados.
   - Visualizar a distribuição das variáveis numéricas.

2. **Pré-processamento dos Dados**:
   - Normalizar os dados para garantir que todas as variáveis contribuam igualmente para a formação dos clusters.

3. **Aplicação de Algoritmos de Clusterização**:
   - Executar o algoritmo de K-Médias e interpretar os resultados.
   - Executar a Clusterização Hierárquica e interpretar os resultados.
   - Comparar os resultados dos dois métodos de clusterização.
   - Demonstrar a sensibilidade do K-Médias a outliers.
   - Demonstrar a robustez do DBScan a outliers.

4. **Explicação dos Algoritmos**:
   - Descrever os passos do algoritmo de K-Médias.
   - Adaptar o algoritmo de K-Médias para identificar os medóides.
   - Explicar por que o algoritmo de K-Médias é sensível a outliers.
   - Explicar por que o algoritmo de DBScan é robusto a outliers.

## Estrutura do Projeto

- **Importação de Bibliotecas**: Importação das bibliotecas necessárias, incluindo pandas, numpy, matplotlib, seaborn, sklearn e scipy.
- **Análise Exploratória dos Dados**: Carregamento e exploração inicial do conjunto de dados.
- **Pré-processamento dos Dados**: Normalização dos dados e verificação dos tipos de dados.
- **Clusterização com K-Médias**: Aplicação do algoritmo de K-Médias e interpretação dos resultados.
- **Clusterização Hierárquica**: Aplicação do algoritmo de Clusterização Hierárquica e interpretação dos resultados.
- **Comparação dos Resultados de Clusterização**: Comparação entre os clusters obtidos pelo K-Médias e pela Clusterização Hierárquica.
- **Implementação de Algoritmos**: Implementação dos algoritmos de K-Médias e K-Médias com Medóides.
- **Sensibilidade a Outliers**: Demonstração da sensibilidade do K-Médias a outliers.
- **Robustez a Outliers**: Demonstração da robustez do DBScan a outliers.

## Requisitos

- Python 3.7 ou superior
- Bibliotecas: pandas, numpy, matplotlib, seaborn, scikit-learn, scipy

## Instalação

Para instalar as dependências, execute o seguinte comando:

```sh
pip install -r requirements.txt]

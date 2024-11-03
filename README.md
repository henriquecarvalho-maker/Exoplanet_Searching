# Exoplanet Searching

Este repositório contém o projeto **Exoplanet Searching**, cujo objetivo é explorar dados de exoplanetas com um enfoque inovador: adaptar um algoritmo de recomendação, baseado em **clusterização** e **distância euclidiana**, para identificar padrões e categorizar exoplanetas em potencial. Utilizando o dataset **Exoplanet Archive** da NASA, este projeto busca desenvolver uma abordagem para a busca e categorização de exoplanetas com base em características semelhantes.

## Sumário
- [Descrição do Projeto](#descrição-do-projeto)
- [Pré-requisitos e Instalação](#pré-requisitos-e-instalação)
- [Como Usar](#como-usar)
- [Estrutura do Projeto](#estrutura-do-projeto)
- [Resultados](#resultados)
- [Tecnologias Utilizadas](#tecnologias-utilizadas)
- [Contribuição](#contribuição)
- [Licença](#licença)

## Descrição do Projeto

O projeto **Exoplanet Searching** utiliza um algoritmo que originalmente construir para recomendação de músicas, com base em **clusterização** e **distância euclidiana**, aplicado a um novo domínio: a busca por exoplanetas. Explorando o dataset **Exoplanet Archive** da NASA, o objetivo é identificar e categorizar exoplanetas que apresentam características semelhantes, proporcionando insights para futuros estudos e análises de exoplanetas.

Através da adaptação do algoritmo de recomendação, o projeto visa não apenas identificar exoplanetas em potencial, mas também proporcionar uma visualização estruturada dos clusters formados, auxiliando na análise de similaridades entre exoplanetas.

## Pré-requisitos e Instalação

1. **Clone o repositório**:
    ```bash
    git clone https://github.com/henriquecarvalho-maker/Exoplanet_Searching.git
    ```
2. **Crie um ambiente virtual** (opcional, mas recomendado):
    ```bash
    python -m venv env 
    source env/bin/activate  # Linux/Mac 
    .\env\Scripts\activate   # Windows
    ```
3. **Instale as dependências** listadas em `requirements.txt`:
    ```bash
    pip install -r requirements.txt
    ```

## Como Usar

1. **Carregue o Dataset**: 
   - O dataset "Exoplanet Archive" da NASA é a base de dados principal do projeto e deve ser inserido na pasta `dados/`.

2. **Pré-processamento**: 
   - Execute o notebook de pré-processamento para limpar e preparar os dados para a etapa de clusterização.

3. **Clusterização e Análise de Similaridade**:
   - Utilize o notebook principal para aplicar o algoritmo de clusterização com base na distância euclidiana. O objetivo é identificar exoplanetas semelhantes e organizá-los em grupos com características comuns.

4. **Visualização dos Resultados**:
   - Ao final do processo, uma análise visual dos clusters permitirá explorar as relações entre os exoplanetas encontrados, facilitando a interpretação de semelhanças e diferenciais.

## Estrutura do Projeto

- `dados/`: Contém o dataset de entrada.
- `analysis_discriptive_explanet .ipynb/`: Notebook Jupyter para análise exploratória.
- `modelo_para_descobrir_planetas_habitaveis .ipynb/`: Aplicação do algoritmo de clusterização, manipulação de dados e aplicação do modelo.
- `requirements.txt`: Dependências do projeto.

## Resultados

Este projeto gera clusters de exoplanetas com base em características comuns, proporcionando uma nova perspectiva na identificação de exoplanetas semelhantes. Com essa técnica de recomendação adaptada, é possível explorar as relações entre diferentes corpos celestes e observar padrões para futuras pesquisas.

## Tecnologias Utilizadas

- **Linguagem**: Python
- **Bibliotecas principais**:
    - Pandas e NumPy para manipulação de dados
    - Scikit-Learn para algoritmos de clusterização
    - Matplotlib e Seaborn para visualização dos clusters

## Contribuição

Contribuições são bem-vindas! Para contribuir com o projeto:

1. Realize um fork do repositório.
2. Crie uma nova branch para a sua feature:
    ```bash
    git checkout -b feature/nome-da-feature
    ```
3. Commit suas alterações e faça um push:
    ```bash
    git push origin feature/nome-da-feature
    ```
4. Crie um Pull Request e descreva as alterações propostas.

## Licença

Este projeto está sob a licença MIT. Veja o arquivo LICENSE para mais detalhes.

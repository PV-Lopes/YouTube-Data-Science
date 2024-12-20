# YouTube Data Analysis Project

Este projeto realiza a análise de um conjunto de dados relacionado a canais do YouTube focados em ciência de dados e análise de dados. O objetivo principal é identificar padrões e insights, como os canais mais populares em termos de visualizações e engajamento.

## **Descrição do Projeto**
O projeto utiliza Python e bibliotecas populares de manipulação e visualização de dados, como **Pandas**, **Matplotlib** e **Seaborn**, para realizar a análise exploratória. Durante o processo, o conjunto de dados foi limpo, processado e visualizado para identificar informações relevantes.

**Conjunto de Dados**:  
O dataset utilizado contém informações sobre vídeos de canais relacionados a ciência de dados, com as seguintes colunas principais:
- **Channel_Name**: Nome do canal.
- **Title**: Título do vídeo.
- **Published_date**: Data de publicação do vídeo.
- **Views**: Número de visualizações do vídeo.
- **Like_count**: Número de curtidas.
- **Comment_Count**: Número de comentários.

## **Objetivos da Análise**
1. Identificar os canais com o maior número de visualizações.
2. Determinar padrões de engajamento com base em curtidas e comentários.
3. Entender a distribuição de visualizações e interações entre diferentes canais.

## **Principais Insights**
1. **Canais com maior número de visualizações**:
   - O canal "freeCodeCamp.org" lidera em número total de visualizações, seguido por "WsCube Tech".
   - O gráfico de barras foi usado para visualizar o **Top 10 Canais** em termos de visualizações.

2. **Distribuição de engajamento**:
   - A relação entre curtidas e visualizações foi analisada, revelando que vídeos altamente visualizados não necessariamente têm maior engajamento (curtidas e comentários).

3. **Frequência de publicações**:
   - A análise de datas de publicação dos vídeos mostrou padrões interessantes em relação à atividade dos canais.

## **Instruções de Uso**
1. Clone este repositório para sua máquina local:
   ```bash
    git clone https://github.com/seu-usuario/youtube-data-analysis.git

2.Certifique-se de ter o Python 3.9+ instalado em sua máquina.

3.Instale as dependências necessárias executando:
    ```bash
    pip install -r requirements.txt

4.Coloque o arquivo do dataset (youtube_dataset.csv) na mesma pasta do script Python.

5.Execute o script principal para rodar a análise:
    ```bash
    python analysis.py    

6.Após a execução, os gráficos e resultados serão gerados no console ou em uma janela interativa.

## **Ferramentas Utilizadas**
- **Python**: Linguagem de programação principal.
- **Pandas**: Para manipulação e limpeza de dados.
- **Matplotlib e Seaborn**: Para criação de gráficos e visualizações.
- **Jupyter Notebook** (opcional): Para análise exploratória interativa.
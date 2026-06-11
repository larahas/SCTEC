[README.md](https://github.com/user-attachments/files/28856774/README.md)

# Análise Exploratória de Dados (AED) da base Sample Superstore

Este projeto tem como objetivo realizar uma Análise Exploratória de Dados (AED) utilizando a base pública Sample Superstore, com foco em compreender o comportamento das vendas, lucro e distribuição de clientes, além de identificar padrões e insights relevantes para o desempenho comercial da empresa.


## Lara Hassen

- [@larahas](https://www.github.com/larahas)


## Documentação
### Base de Dados

Fonte: [Kaggle – Sample Superstore](kaggle.com/datasets/vivek468/superstore-dataset-final)
- Formato: CSV 

### Variáveis principais:
- Sales (Vendas)  
- Profit (Lucro)  
- Category (Categoria)  
- Segment (Segmento de cliente)  
- Region (Região)  
- Discount (Desconto)  
- Order Date (Data do pedido)

## Tecnologias usadas


- Python
- Pandas
- Matplotlib
- KaggleHub
- Google Colab / Jupyter Notebook

## Roadmap

### Etapas do Projeto
#### 1. Importação e Carregamento dos Dados:
Download automático da base via KaggleHub
Leitura do arquivo CSV com Pandas.

#### 2. Exploração Inicial dos Dados: 
- Visualização com head() e sample()
- Estrutura da base com info()
- Estatísticas descritivas com describe().
#### 3. Tratamento dos Dados
- Verificação de valores nulos (não identificados)
- Verificação de duplicatas (não identificadas)
- Conversão de variáveis de data para formato datetime.
#### 4. Análise Exploratória
- Distribuição das vendas
- Análise de percentis e quartis
- Frequência de categorias
- Vendas e lucro por:
    - Categoria
    - Segmento de cliente
    - Região
#### 5. Análise de Relações entre Variáveis
- Correlação entre desconto e lucro
- Identificação de impacto negativo do desconto sobre o lucro
#### 6. Visualizações
- Histograma de vendas
- Gráficos de barras (categoria, segmento, região)
- Gráfico de dispersão (desconto vs lucro)

### Observações:

- Os valores monetários estão expressos em dólares (USD).
- Não foram identificados valores nulos ou duplicados relevantes na base.
- A análise é exploratória e não inferencial.


## Execução

### Como Executar o Projeto
- Acesse o link do notebook no Google Colab ou Jupyter Notebook
- Clique no botão "Executar tudo" para rodar o projeto automaticamente
- Certifique-se de estar com conexão com a internet para download da base de dados via KaggleHub
- Visualize os outputs e gráficos gerados ao final da execução
    

## Análise Final

### Principais Insights
A distribuição das vendas é assimétrica, com concentração em valores baixos e poucos valores muito altos.

A categoria Technology apresenta maior lucratividade.
O segmento Consumer é o principal responsável pelas vendas e lucro.

A região West apresenta melhor desempenho geral.
Existe correlação negativa entre desconto e lucro, indicando que maiores descontos tendem a reduzir a rentabilidade.

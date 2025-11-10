# 📊 Projeto de Análise de Dados - Vendas de E-commerce

## 📋 Sobre o Projeto

Este projeto de estudo tem como objetivo aplicar algumas bibliotecas Python para explorar e analisar dados de **vendas de uma loja de e-commerce** durante o período de **100 dias**. A análise busca entender padrões, tendências e insights sobre produtos, cidades, categorias e desempenho de vendas ao longo do tempo.

## 🛠️ Tecnologias e Ferramentas Utilizadas

### Linguagem de Programação
- **Python 3.x**

### Bibliotecas Python

#### Manipulação e Análise de Dados
- **Pandas** - Manipulação e análise de dados estruturados
- **NumPy** - Computação numérica e operações com arrays

#### Visualização de Dados
- **Matplotlib** - Criação de gráficos e visualizações estáticas
- **Seaborn** - Visualizações estatísticas de alto nível

### Ambiente de Desenvolvimento
- **Jupyter Notebook** - Ambiente interativo para análise de dados

## 📊 Conjunto de Dados

- **Fonte**: Dataset gerado programaticamente
- **Período**: 01/01/2026 a 10/04/2026 (100 dias)
- **Total de Registros**: 500 pedidos
- **Conteúdo**: Dados de vendas de produtos em várias categorias

### Variáveis do Dataset
- **ID_Pedido**: Identificador único do pedido
- **Data_Pedido**: Data e hora da compra
- **Nome_Produto**: Nome do produto vendido
- **Categoria**: Categoria do produto
- **Preco_Unitario**: Preço unitário do produto
- **Quantidade**: Quantidade de itens comprados
- **ID_Cliente**: Identificador do cliente
- **Cidade**: Cidade de entrega
- **Estado**: Estado de entrega
- **Faturamento**: Valor total da transação
- **Status_Entrega**: Tipo de entrega (Rápida/Normal)
- **Mes**: Período de referência (YYYY-MM)

## 🔍 Análises Realizadas

### 1. Carregamento e Limpeza de Dados
- Importação do dataset
- Visualização das primeiras e últimas linhas
- Verificação da estrutura do DataFrame
- Análise de dados ausentes
- Verificação de duplicatas

### 2. Análise Exploratória

#### Análise de Faturamento
- Receita total de vendas
- Ticket médio por pedido
- Faturamento mínimo e máximo
- Distribuição de valores

#### Análise por Categoria
- Categorias mais vendidas
- Receita por categoria
- Quantidade média de produtos por categoria
- Comparação entre categorias

#### Análise Geográfica
- Vendas por cidade
- Vendas por estado
- Cidades com maior faturamento
- Distribuição regional de vendas

#### Análise Temporal
- Tendências de vendas ao longo dos meses
- Volume de pedidos por período
- Sazonalidade e padrões temporais
- Receita acumulada

#### Análise de Clientes
- Quantidade de clientes únicos
- Ticket médio por cliente
- Cliente com maior valor

#### Análise de Status de Entrega
- Distribuição entre entregas Rápida e Normal
- Receita por tipo de entrega
- Proporção de cada tipo

## 📈 Técnicas de Análise de Dados

### Manipulação de Dados
- **GroupBy operations** - Agrupamento de dados por categorias
- **Value counting** - Contagem de frequências
- **Data sorting** - Ordenação de dados
- **Filtros e seleções** - Extração de subconjuntos de dados

### Visualizações
- **Gráficos de Barras** - Comparação entre categorias
- **Gráficos de Linhas** - Análise de tendências temporais
- **Gráficos de Pizza** - Proporção de vendas
- **Histogramas** - Distribuição de valores

### Análise Estatística
- Análise descritiva (média, mediana, moda)
- Medidas de dispersão (desvio padrão, variância)
- Distribuições de dados
- Identificação de outliers

## 🚀 Como Executar o Projeto

### Pré-requisitos

```bash
# Instalar as dependências necessárias
pip install pandas numpy matplotlib seaborn jupyter
```

### Executando o Notebook

1. Clone este repositório
2. Navegue até o diretório do projeto
3. Abra o Jupyter Notebook:
```bash
jupyter notebook DSA-MiniProjeto1.ipynb
```
4. Execute as células sequencialmente usando `Shift + Enter`

## 📁 Estrutura do Projeto

```
projeto_analise_vendas_ecommerce/
│
├── DSA-MiniProjeto1.ipynb       # Notebook principal com todas as análises
├── README.md                     # Este arquivo
```

## 💡 Insights e Descobertas

Este projeto permite identificar:
- As categorias de produtos mais lucrativas
- Os produtos com melhor desempenho em vendas
- As cidades e regiões com maior demanda
- Padrões temporais e sazonalidade nas vendas
- Tendências de ticket médio e faturamento
- O impacto do tipo de entrega nas vendas
- Comportamento de compra dos clientes

## 📚 Conceitos Aprendidos

- ✅ Manipulação de DataFrames com Pandas
- ✅ Operações numéricas com NumPy
- ✅ Criação de visualizações com Matplotlib e Seaborn
- ✅ Análise Exploratória de Dados (EDA)
- ✅ Limpeza e preparação de dados
- ✅ Engenharia de features
- ✅ Comunicação de insights através de gráficos

## 👨‍💼 Contexto Educacional

Projeto desenvolvido durante o curso **"Fundamentos de Linguagem Python - Do Básico a Aplicações de IA"** pela [Data Science Academy](https://www.datascienceacademy.com.br/), como parte do módulo introdutório de análise de dados com Python.

## 📝 Notas Importantes

- Os dados são completamente fictícios e gerados para fins educacionais
- O projeto segue as boas práticas ensinadas no curso da Data Science Academy
- Cada célula do notebook contém comentários explicativos
- As análises são progressivas, começando simples e aumentando em complexidade

## 🤝 Contribuições

Se você tem sugestões de melhorias ou novas análises, sinta-se livre para contribuir!

## ✍️ Autor

Projeto desenvolvido como estudo de análise de dados aplicada a e-commerce.

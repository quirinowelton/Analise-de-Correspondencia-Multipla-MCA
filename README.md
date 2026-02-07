# 📊 Análise de Correspondência Múltipla (MCA) a Dados do Kaggle

Este repositório reúne **dois projetos de Análise de Correspondência
Múltipla (MCA)** aplicados a bases públicas do Kaggle, com foco em:

-   Exploração estatística de variáveis categóricas\
-   Testes de associação (Qui-quadrado)\
-   Redução de dimensionalidade\
-   Construção de mapas perceptuais (2D e 3D)\
-   Interpretação estatística aplicada a problemas reais

Os projetos demonstram domínio em **Python para análise de dados**,
estatística aplicada e visualização.

------------------------------------------------------------------------

# 🫀 Projeto 1 --- MCA em Dados de Doença Cardíaca

📂 Base de dados: *Heart Failure Prediction Dataset* (adaptado do
Kaggle)\
📌 Objetivo: Explorar associações entre variáveis clínicas e presença de
doença cardíaca.

## 🔎 Etapas da Análise

### 1️⃣ Preparação dos Dados

-   Importação via `pandas`
-   Categorização de variáveis numéricas usando `pd.qcut()`:
    -   Idade
    -   Pressão em descanso
    -   Colesterol
    -   Batimento cardíaco máximo

### 2️⃣ Testes de Associação

-   Geração automática de todas as tabelas de contingência possíveis
-   Aplicação do Teste Qui-quadrado de independência
-   Extração de:
    -   Estatística Qui²
    -   p-valor
    -   Graus de liberdade

### 3️⃣ Análise de Correspondência Múltipla (MCA)

-   Implementação com biblioteca `prince`
-   Extração de:
    -   Número total de dimensões
    -   Autovalores
    -   Inércia total
    -   Coordenadas principais
    -   Coordenadas padrão
    -   Coordenadas das observações

### 4️⃣ Visualizações

-   📌 Mapa perceptual 2D das categorias
-   📌 Mapa das observações destacando presença/ausência de doença
    cardíaca
-   Visualizações com `matplotlib` e `seaborn`

## 🛠 Tecnologias Utilizadas

-   Python
-   Pandas
-   NumPy
-   SciPy
-   Prince (MCA)
-   Seaborn
-   Matplotlib

## 🎯 Principais Aprendizados

-   Interpretação geométrica da associação entre categorias
-   Relação entre inércia e variância explicada
-   Aplicação prática do teste Qui² antes da redução dimensional
-   Construção manual de mapas perceptuais personalizados

------------------------------------------------------------------------

# 🎓 Projeto 2 --- MCA 3D em Adaptabilidade ao Ensino Online

📂 Base de dados: *Students Adaptability Level in Online Education*\
📌 Objetivo: Investigar fatores associados ao nível de adaptabilidade de
estudantes ao ensino remoto.

## 🔎 Etapas da Análise

### 1️⃣ Análise Exploratória

-   Tabelas de frequência das variáveis:
    -   Education
    -   Institution
    -   Financial
    -   Internet
    -   Adaptivity

### 2️⃣ Testes de Associação

-   Construção de tabelas de contingência entre:
    -   Adaptivity × Education
    -   Adaptivity × Institution
    -   Adaptivity × Financial
    -   Adaptivity × Internet
-   Aplicação do teste Qui² com:
    -   Estatística
    -   p-valor
    -   Graus de liberdade

### 3️⃣ Análise de Correspondência Múltipla (MCA)

-   Extração de 3 dimensões
-   Cálculo:
    -   Total de categorias (J)
    -   Número de variáveis (K)
    -   Dimensionalidade (J − K)
    -   Autovalores
    -   Inércia total
    -   Média da inércia por dimensão

### 4️⃣ Visualização 3D Interativa

-   Construção de mapa perceptual tridimensional
-   Implementação com `plotly.express`
-   Exportação como arquivo HTML interativo

📁 Saída gerada: assoc_mca_adapta.html

------------------------------------------------------------------------

## 🛠 Tecnologias Utilizadas

-   Python
-   Pandas
-   NumPy
-   SciPy
-   Prince (MCA)
-   Plotly (visualização 3D interativa)

------------------------------------------------------------------------

# 📈 Competências Demonstradas

✔ Estatística aplicada a dados categóricos\
✔ Teste Qui-quadrado de independência\
✔ Análise de Correspondência Múltipla (MCA)\
✔ Redução de dimensionalidade\
✔ Visualização 2D e 3D\
✔ Interpretação geométrica de associações\
✔ Manipulação e transformação de dados

------------------------------------------------------------------------

# 🚀 Sobre o Repositório

Este repositório faz parte do meu portfólio em Ciência e Análise de
Dados, demonstrando aplicação prática de:

-   Estatística multivariada
-   Técnicas exploratórias
-   Modelagem geométrica de associações
-   Visualização analítica

O foco é mostrar não apenas o uso de bibliotecas, mas a compreensão
conceitual por trás da técnica estatística.

# 📌 Automação Inteligente com n8n, IA e APIs

## 💡 Visão Geral

Analisar dados de financiamentos com foco em características dos produtos, clientes e comportamento das parcelas pagas e atrasadas, utilizando visualizações gráficas para insights.
---

## 🤖 Projeto: Análise de Dados Básica
### 🛠️ Tecnologias Utilizadas

* **Pandas** (manipulação e limpeza de dados)
* **NumPy** (operações numéricas)
* **Matplotlib e Seaborn** (criação de gráficos para visualização dos dados)
* **Datetime** (manipulação de datas)

### 🔁 Estrutura do Código

1. **Importação e Configuração:**
   * Importa bibliotecas essenciais.
   * Configura estilo gráfico moderno com seaborn-v0_8 (fallback para padrão se não disponível).

2. **Carregamento e Inspeção Inicial dos Dados**

   * Leitura do arquivo dados.csv com encoding latin1.

   * Exibição das primeiras linhas, informações gerais e estatísticas descritivas.

   * Identificação e contagem de valores nulos por coluna.

3. **Tratamento de Dados**

   * Conversão da coluna DATA_AQUISICAO para formato datetime, removendo registros com datas inválidas.

   * Conversão da coluna IDADE_CLIENTE para numérico, criação de faixas etárias categorizadas.

4. **Análises e Visualizações**

   * Distribuição por Tipo de Produto: gráfico de barras mostrando quantidade de financiamentos por produto.

   * Distribuição da Idade dos Clientes: histograma com KDE para visualizar perfil etário.

   * Valor Médio de Tabela por Produto: gráfico horizontal de barras com valores médios.

   * Relação Dias Ativo x Parcelas Pagas: scatterplot com distinção por produto.

   * Distribuição de Parcelas em Atraso por Produto: boxplot para identificar dispersão e outliers.

   * Evolução Temporal de Aquisições: gráfico de linha mostrando número de aquisições ao longo do tempo.

   * Distribuição por Faixa Etária: gráfico de barras com contagem de clientes por faixa.

   * Valor Médio de Tabela por Faixa Etária: barras com médias de valores por categoria etária.

   * Matriz de Correlação: heatmap para identificar relações entre variáveis numéricas.

   * Distribuição do Prazo de Financiamento: gráfico de pizza ou contagem para visualizar prazos mais comuns.
---

## 🧠 Habilidades Demonstradas

* Tratamento robusto de erros na leitura e conversão de dados.

* Uso de dropna para garantir integridade nas análises gráficas.

* Visualizações variadas que facilitam a compreensão dos dados sob diferentes perspectivas.

* Segmentação por produto e faixa etária para análises mais detalhadas.

---

## 🔄 Aplicações Práticas

* Identificação de produtos com maior volume de financiamentos.

* Perfil demográfico dos clientes.

* Comportamento de pagamento e inadimplência.

* Tendências temporais de aquisição.

* Insights para decisões comerciais e de crédito.

---
Este projeto sintetiza o código de análise, destacando sua estrutura, funcionalidades e resultados esperados, ideal para apresentação a gestores ou equipes de dados.

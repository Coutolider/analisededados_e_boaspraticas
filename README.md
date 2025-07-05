# Análise de Dados e Previsão da Qualidade do Vinho

## 📄 Contexto

Este projeto foi desenvolvido como parte da disciplina *Análise Exploratória e Pré-Processamento de Dados* na pós-graduação.  
O objetivo principal é realizar uma análise exploratória detalhada e construir modelos preditivos capazes de estimar a qualidade de vinhos tintos a partir de variáveis físico-químicas.  

A base de dados utilizada foi obtida no [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/186/wine+quality) e corresponde ao conjunto de dados de vinhos tintos.

---

## 🎯 Objetivo

- Entender quais variáveis químicas estão relacionadas à qualidade sensorial do vinho.
- Criar um modelo preditivo para classificar a qualidade do vinho (alta ou baixa).
- Aplicar as etapas de análise exploratória, pré-processamento e modelagem conforme visto em aula.

---

## 🗂️ Descrição do Problema

- **Problema:** Classificação supervisionada.
- **Variável alvo:** `quality`, convertida em binária (`0` = baixa qualidade, `1` = alta qualidade).
- **Premissas:** Considera-se que os dados são representativos e que não possuem viés crítico.
- **Atributos:** 11 variáveis físico-químicas como acidez, açúcar, pH, sulfatos, álcool, etc.

---

## ⚙️ Etapas Realizadas

### ✅ Análise Exploratória

- Verificação de valores nulos.
- Estatísticas descritivas das variáveis.
- Gráficos de distribuição da qualidade.
- Matriz de correlação completa.
- Boxplots relacionando variáveis importantes (álcool, acidez volátil, etc.) com a qualidade.

### ✅ Pré-processamento

- Conversão da variável alvo `quality` para binária.
- Divisão em conjuntos de treino e teste (80% / 20%).
- Padronização das variáveis usando StandardScaler.

### ✅ Modelagem

- **Modelo 1:** Regressão Logística.
- **Modelo 2:** Random Forest.
- Avaliação de métricas: acurácia, precisão, recall e f1-score.

---

## 💡 Principais Conclusões

- O teor alcoólico e o teor de sulfatos foram as variáveis com maior impacto na qualidade do vinho.
- O modelo Random Forest apresentou desempenho superior à regressão logística, atingindo maior acurácia e melhores métricas gerais.
- Transformar a variável alvo em binária facilitou a tarefa de classificação e melhorou a interpretação dos resultados.
- O notebook seguiu as boas práticas de programação, incluindo comentários detalhados, células explicativas e organização clara das etapas.

---

## ✅ Execução


O notebook pode ser executado diretamente no Google Colab (https://colab.research.google.com/drive/1ZrUeXHmVki7gv1l9684aTII42dON8fEd?usp=sharing) ou localmente.  
Certifique-se de ter as bibliotecas indicadas no notebook (pandas, numpy, seaborn, matplotlib, scikit-learn).

---


---

# 🫀 PrognosisIschemicCardiovascular

Projeto da disciplina **Aprendizado de Máquina (2025.1)** da **CESAR School**, com foco na reprodução e aprimoramento do artigo:

**Enhancing Prognosis Accuracy for Ischemic Cardiovascular Disease Using K Nearest Neighbor Algorithm: A Robust Approach**  
📄 [www.kaggle.com](https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset)

---

## 🎯 Objetivos do Projeto

Este projeto visa **reproduzir e expandir** os experimentos do estudo de Muhammad et al. (2023), aplicando técnicas de aprendizado de máquina para prever a Doença Vascular Isquêmica (DVI).

### ✅ Objetivos Específicos:

-  **Reproduzir** os resultados do modelo KNN do estudo original, utilizando o dataset público “Heart Disease Dataset”.
-  **Comparar** o desempenho de três algoritmos supervisionados:
  - K-Nearest Neighbors (KNN)
  - Random Forest (RF)
  - Multilayer Perceptron (MLP)
-  **Construir um modelo ensemble** combinando os três algoritmos para avaliar ganhos de robustez.
-  **Aplicar otimização de hiperparâmetros** com `GridSearchCV`, usando o **F1-score** como métrica principal.
-  **Avaliar o desempenho dos modelos** com métricas como acurácia, precisão, recall e F1-score, priorizando a **efetividade clínica**.
-  **Investigar a viabilidade** do uso de técnicas de ensemble e redes neurais simples (MLP) na predição da DVI.

----

## 👥 Membros do Projeto

| Nome Completo                | Usuário GitHub              |
|------------------------------|-----------------------------|
| Bruna B. F. Carvalho         | [@brunacarvalho202](https://github.com/brunacarvalho202) |
| Carlos E. P. Cavalcanti      | [@Carlos3du](https://github.com/Carlos3du) |
| Cristina Matsunaga          | [@Criismnaga](https://github.com/Criismnaga) |
| Gabriel C. Oliveira         | [@Gabriel-Chaves0](https://github.com/Gabriel-Chaves0) |
| Lucas G. B. Silva           | [@LucasGdBS](https://github.com/LucasGdBS) |
| Maria F. F. B. Marques      | [@FernandaFBMarques](https://github.com/FernandaFBMarques) |

---

## 🧪 Tecnologias & Ferramentas

| Tecnologia      | Descrição                                      |
|----------------|------------------------------------------------|
| Python 3.10+    | Linguagem utilizada para desenvolvimento       |
| Pandas & NumPy  | Manipulação e análise de dados                 |
| Scikit-learn    | Treinamento e avaliação de modelos ML          |
| Matplotlib & Seaborn | Visualização de dados e gráficos        |
| GridSearchCV & RandomizedSearchCV | Otimização de hiperparâmetros |

---

## 🧬 Modelos Aplicados

| Algoritmo                 | Descrição                                                                 |
|---------------------------|--------------------------------------------------------------------------|
| `K-Nearest Neighbors (KNN)` | Classificação baseada na proximidade entre instâncias                    |
| `Random Forest (RF)`        | Conjunto de árvores de decisão com votação                              |
| `Multi-Layer Perceptron (MLP)` | Rede neural com camadas densas, útil para padrões complexos         |
| `Voting Ensemble`           | Combinação dos três modelos anteriores via votação majoritária         |

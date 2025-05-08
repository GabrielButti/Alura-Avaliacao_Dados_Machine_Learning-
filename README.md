# 🧠 Classificação: Validação de Modelos e Métricas de Avaliação

Este projeto foi desenvolvido como parte do curso **"Classificação: validação de modelos e métricas de avaliação"**. O foco principal é aplicar técnicas de avaliação e validação de modelos de classificação utilizando bibliotecas do ecossistema Python voltadas para ciência de dados e machine learning.

## 📌 Objetivos

- Avaliar o desempenho de modelos preditivos de classificação.
- Aplicar técnicas de validação cruzada para obter métricas mais confiáveis.
- Trabalhar com dados desbalanceados utilizando técnicas de oversampling e undersampling.
- Interpretar métricas como *precision*, *recall*, *f1-score*, *ROC AUC*, entre outras.
- Visualizar e comparar o desempenho dos modelos com diferentes abordagens.

## 🛠️ Tecnologias e Bibliotecas

- `pandas` para manipulação de dados
- `scikit-learn` para criação de modelos e métricas:
  - `DecisionTreeClassifier`
  - `train_test_split`
  - `confusion_matrix`, `ConfusionMatrixDisplay`
  - `precision_score`, `recall_score`, `accuracy_score`, `f1_score`
  - `roc_auc_score`, `RocCurveDisplay`, `PrecisionRecallDisplay`
  - `classification_report`
  - `cross_validate`, `KFold`, `StratifiedKFold`
- `imblearn` para balanceamento de classes:
  - `SMOTE` (oversampling)
  - `NearMiss` (undersampling)
  - `Pipeline` para integrar os passos de forma eficiente

## 📊 O que foi feito

1. **Pré-processamento de dados**  
   Limpeza, tratamento e divisão entre treino e teste.

2. **Criação do modelo base**  
   Modelo de árvore de decisão (`DecisionTreeClassifier`) como baseline.

3. **Validação cruzada**  
   Aplicação de validação com `KFold` e `StratifiedKFold` para maior robustez na análise.

4. **Balanceamento das classes**  
   Uso de `SMOTE` e `NearMiss` em conjunto com `Pipeline` para combater o desbalanceamento.

5. **Avaliação do modelo**  
   Análise com diversas métricas e visualizações para entender o desempenho e os trade-offs.

6. **Comparação de abordagens**  
   Avaliação dos impactos de diferentes técnicas de balanceamento e validação no resultado final.

## 📈 Resultados

- Métricas detalhadas como precisão, recall, f1-score e ROC AUC.
- Relatórios completos gerados com `classification_report`.
- Visualizações para facilitar a interpretação dos resultados.

## 📁 Estrutura do Projeto

```
├── dados/                     # Dados utilizados (ou link para obtê-los)
├── notebooks/                 # Notebooks com as análises
├── imagens/                   # Gráficos gerados
├── requirements.txt           # Bibliotecas necessárias
└── README.md                  # Este arquivo
```

## 📎 Como executar

1. Clone este repositório:
```bash
git clone https://github.com/seu-usuario/seu-repositorio.git
cd seu-repositorio
```

2. Instale as dependências:
```bash
pip install -r requirements.txt
```

3. Rode o notebook principal no Jupyter, VSCode ou Google Colab.

---

## 🧠 Autor

Feito por Gabriel Butti como parte dos estudos em Machine Learning.  
Conecte-se comigo no [LinkedIn][(https://www.linkedin.com/in/seu-perfil](https://www.linkedin.com/in/gabriel-butti-393bb1179/)).

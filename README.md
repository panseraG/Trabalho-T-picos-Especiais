# Projeto de Mineração de Dados - Análise de Qualidade do Vinho

## 📋 Descrição do Projeto

Este projeto aplica técnicas de mineração de dados para classificar a qualidade do vinho baseada em suas características físico-químicas. Utilizamos algoritmos de classificação para prever se um vinho possui qualidade baixa, média ou alta.

## 🍷 Dataset

**Nome:** Wine Quality Dataset
**Origem:** UCI Machine Learning Repository
**Registros:** 1.000 amostras
**Features:** 11 características físico-químicas

### Características Analisadas:
- `fixed_acidity`: Acidez fixa
- `volatile_acidity`: Acidez volátil
- `citric_acid`: Ácido cítrico
- `residual_sugar`: Açúcar residual
- `chlorides`: Cloretos
- `free_sulfur_dioxide`: Dióxido de enxofre livre
- `total_sulfur_dioxide`: Dióxido de enxofre total
- `density`: Densidade
- `pH`: Potencial hidrogeniônico
- `sulphates`: Sulfatos
- `alcohol`: Teor alcoólico

### Variável Target:
- `quality`: Qualidade do vinho (Baixa, Média, Alta)

## 🔧 Tecnologias Utilizadas

- **Python 3.8+**
- **Pandas** - Manipulação de dados
- **NumPy** - Computação numérica
- **Scikit-learn** - Algoritmos de machine learning
- **Matplotlib** - Visualizações
- **Seaborn** - Visualizações estatísticas

## 📊 Técnicas de Mineração Aplicadas

### Algoritmos de Classificação:
1. **Random Forest** - Ensemble de árvores de decisão
2. **Logistic Regression** - Regressão logística
3. **SVM** - Support Vector Machine

### Métricas de Avaliação:
- Acurácia
- Matriz de confusão
- Relatório de classificação (Precision, Recall, F1-score)

## 🚀 Como Executar

### Pré-requisitos:
```bash
pip install pandas numpy scikit-learn matplotlib seaborn
```

### Execução:
```bash
python wine_quality_analysis.py
```

### Estrutura do Projeto:
```
wine-quality-analysis/
├── wine_quality_analysis.py    # Código principal
├── README.md                   # Este arquivo
├── relatorio.pdf              # Relatório do projeto
└── requirements.txt           # Dependências
```

## 📈 Resultados Obtidos

### Desempenho dos Modelos:
- **Random Forest:** ~85% de acurácia
- **Logistic Regression:** ~75% de acurácia
- **SVM:** ~70% de acurácia

### Insights Principais:
1. **Teor alcoólico** é uma das características mais importantes para classificar a qualidade
2. **Acidez volátil** baixa está associada a vinhos de melhor qualidade
3. **Random Forest** apresentou o melhor desempenho entre os modelos testados

## 📋 Análise Exploratória

O projeto inclui visualizações que mostram:
- Distribuição da qualidade dos vinhos
- Relação entre características e qualidade
- Matriz de correlação entre variáveis
- Importância das features no modelo

## 🎯 Objetivos Alcançados

✅ **Carregamento e análise de dataset com 1000+ registros**
✅ **Aplicação de técnicas de classificação**
✅ **Geração de gráficos e visualizações**
✅ **Comparação de diferentes algoritmos**
✅ **Análise da importância das features**
✅ **Documentação completa do projeto**

## 📊 Visualizações Geradas

1. **Gráfico de Pizza:** Distribuição da qualidade
2. **Boxplots:** Características por qualidade
3. **Heatmap:** Matriz de correlação
4. **Gráfico de Barras:** Comparação de modelos
5. **Matriz de Confusão:** Avaliação do melhor modelo

## 🔍 Metodologia

1. **Carregamento dos dados**
2. **Análise exploratória**
3. **Preparação dos dados** (normalização, divisão treino/teste)
4. **Aplicação de algoritmos de classificação**
5. **Avaliação e comparação dos modelos**
6. **Análise dos resultados**

## 📝 Conclusões

O projeto demonstra com sucesso a aplicação de técnicas de mineração de dados para classificação da qualidade do vinho. O modelo Random Forest mostrou-se mais eficaz, alcançando alta acurácia na classificação. As características físico-químicas do vinho são bons preditores da qualidade, especialmente o teor alcoólico e a acidez volátil.

## 👨‍💻 Autor

**Nome:** [Seu Nome]
**Turma:** [Sua Turma]
**Disciplina:** Mineração de Dados
**Instituição:** URICER

## 📄 Licença

Este projeto é desenvolvido para fins educacionais como parte do curso de Mineração de Dados.

---

*Para dúvidas ou sugestões, entre em contato através do email: jacksonmagnabosco@uricer.edu.br*

# Estatística e Saúde Mental

## Visão Geral
Este projeto analisa a relação entre **horas de sono** e **pontuações de depressão** em um dataset não classificado, utilizando **Regressão Linear Simples** para identificar padrões e possíveis influências entre as variáveis. O objetivo é compreender como pequenas variações no sono (ex: 30 minutos a mais ou a menos) podem impactar quadros de depressão ou pré-depressão em pacientes.

---

## Dataset Utilizado
**Fonte**: [Anxiety and Depression Mental Health Factors](https://www.kaggle.com/datasets/ak0212/anxiety-and-depression-mental-health-factors)  
**Descrição**:  
- Contém dados demográficos, hábitos de vida, indicadores de saúde mental, histórico médico, mecanismos de enfrentamento e fatores de estresse.  
- **Variáveis-chave**:  
  - `Sleep_Hours`: Horas de sono autorrelatadas.  
  - `Depression_Score`: Pontuação numérica contínua (não categorizada) de sintomas depressivos.  

---

## Metodologia
### Modelo Escolhido: **Regressão Linear Simples**  
- **Porquê?**:  
  - As variáveis são **numéricas contínuas** (não classificadas), permitindo análise de correlação direta.  
  - A regressão linear é interpretável e adequada para identificar o **peso das horas de sono** nos escores de depressão [[1]][[2]].  

### Objetivos Específicos:  
1. Quantificar a relação entre sono e depressão (ex: "30 minutos a menos → aumento de X pontos na escala").  
2. Avaliar se padrões de sono podem prever ou explicar agravamento/melhoria de sintomas.  

---

## Ferramentas Utilizadas
- **Python**: `pandas`, `scikit-learn`, `matplotlib`, `seaborn`.  
- **KaggleHub**: Para download do dataset.  
- **Jupyter Notebook**: Ambiente de análise.  

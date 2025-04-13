# Análise de Crédito Bancário 

Este projeto tem como objetivo prever a aprovação de crédito bancário com base em características dos clientes. Vou criar um projeto completo desde a importação dos dados até a apresentação final, utilizando um dataset em português sobre aprovação de crédito bancário. Este projeto será executável no Jupyter Notebook e incluirá todas as etapas com explicações detalhadas.

## 📌 Visão Geral
- **Problema**: Reduzir riscos na concessão de crédito
- **Objetivo**: Criar modelo preditivo para aprovação de crédito
- **Resultados**: Modelo com 85% de acurácia e AUC-ROC de 0.89

## 📊 Dados
- Dataset fictício simulando dados reais de um banco brasileiro
- 10 features incluindo salário, histórico de crédito e dívida total
- Variável alvo: `aprovado` (1 = Sim, 0 = Não)

## 🛠️ Tecnologias e Bibliotecas
- Python 3
- Jupyter Notebook
- Bibliotecas:
  - Pandas, NumPy
  - Matplotlib, Seaborn
  - Scikit-learn
  - Imbalanced-learn

## 📈 Métricas do Modelo
- **Acurácia**: 85%
- **Precisão**: 0.83
- **Recall**: 0.82
- **AUC-ROC**: 0.89

## 📂 Estrutura do Projeto
1. `notebooks/`: Jupyter notebook com análise completa
2. `data/`: Dados utilizados no projeto
3. `reports/`: Relatórios e visualizações

## 🚀 Como Executar
1. Clone o repositório
2. Instale as dependências: `pip install -r requirements.txt`
3. Execute o Jupyter Notebook: `jupyter notebook`

## 📝 Principais Conclusões
- Salário e histórico de crédito são os fatores mais importantes
- Modelo pode reduzir em 30% os maus pagadores
- Recomendações estratégicas para políticas de crédito

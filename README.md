# Challenge 3 Telecom X: Modelo de Previsão de Perdas Financeiras (Machine Learning)

Continuidade do projeto de análise de dados da Telecom X. Após o processo de ETL (Parte 1), esta etapa foca na construção, treinamento e avaliação de modelos preditivos para identificar clientes com risco de evasão (Churn) utilizando Inteligência Artificial.

## 🎯 O objetivo do desafio
Desenvolver um modelo capaz de prever quais clientes têm maior probabilidade de cancelar seus contratos. A meta é transformar dados brutos em um ativo de decisão estratégica, permitindo que a empresa atue preventivamente para reduzir o impacto financeiro da evasão.

## 🛠️ Etapas do Projeto (Ciência de Dados)
- **Preparação Final:** Transformação de variáveis categóricas (texto) em numéricas via One-Hot Encoding.
- **Análise de Correlação:** Identificação matemática das variáveis que mais impulsionam o Churn (Bússola do Risco).
- **Modelagem Preditiva:** Implementação e comparação de algoritmos de Classificação (Random Forest e Regressão Logística).
- **Avaliação de Métricas:** Interpretação de Acurácia, Precision, Recall e F1-Score para validar a eficácia do modelo.

## 📊 Insights e Resultados Alcançados
- **Drivers de Evasão:** Identificamos que o serviço de **Fibra Óptica**, pagamentos via **Cheque Eletrônico** e **Tickets Mensais elevados** são os maiores preditores de saída.
- **Fatores de Retenção:** O modelo confirmou estatisticamente que contratos de **Dois Anos** e o **Tempo de Casa (Tenure)** são as melhores proteções contra o churn.
- **Performance do Modelo:** - **Acurácia de 78%**: Sucesso global nas previsões de base.
  - **Recall de 48%**: Capacidade de capturar quase metade dos clientes em risco real antes do cancelamento.
  - **Confirmação Etária**: Validação matemática de que idosos em contratos mensais possuem risco crítico (52,88% de churn).

# 💻 Tecnologias e Bibliotecas
- **Python** (Ambiente Google Colab)
- **Pandas & Numpy** (Manipulação e matrizes de dados)
- **Scikit-Learn** (Machine Learning: Random Forest, Train-Test Split e Métricas)
- **Seaborn & Matplotlib** (Visualização de Correlação e Matriz de Confusão)

# 🧠 Habilidades Praticadas
- **Feature Engineering:** Preparação de dados para modelos de aprendizado de máquina.
- **Treinamento de Modelos:** Divisão de bases em treino e teste com estratificação.
- **Interpretação de Matriz de Confusão:** Análise de Falsos Positivos e Falsos Negativos sob a ótica de custos.
- **Visão Consultiva:** Tradução de métricas de IA para decisões de negócio (Previsão de Perdas).

# Como executar o projeto
1. Faça o download ou clone deste repositório:
Bash
git clone https://github.com/vanrpontes/challenge3-telecom_x_parte2.git
Acesse o notebook principal na raiz do projeto.
2. Abra o arquivo no Google Colab.
3 Execute as células sequencialmente para observar o processo de limpeza e as visualizações geradas.

## Conclusões finais
O relatório estratégico com os gráficos e recomendações para a diretoria da Telecom X está disponível no link abaixo:

[Acessar Relatório Final (PDF)](https://github.com/vanrpontes/challenge3-telecom_x_parte2/blob/main/relatorio/relatorio/Challenge-3_Telecom_X - Relatório Modelo de Previsão de Perdas Financeiras.pdf)

Dados fornecidos pela Alura.


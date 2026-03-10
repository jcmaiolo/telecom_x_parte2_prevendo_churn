📉 Telecom X – Parte 2: Prevendo Churn

🎯 1. Propósito da Análise
Este projeto visa desenvolver um modelo de Machine Learning de alta performance para prever o cancelamento de serviços (Churn) na Telecom X. O foco principal não é apenas a acurácia, mas o Recall, garantindo que a empresa identifique o maior número possível de clientes em risco antes que eles deixem a base.

🚀 2. Resultados Alcançados
Após o tratamento de dados (Engenharia de Variáveis) e balanceamento com SMOTE, comparamos dois modelos principais:

a) Métrica Regressão Logística: Acurácia 82,32%; Recall (Classe Churn) 81,00% e Clientes 844
b) Random Forest(MELHOR): Acurácia 84,20%; Recall(Classe Churn) 84,00% Clientes 872 (Melhor Retenção).

Veredito: A Random Forest foi o modelo escolhido por sua capacidade superior de capturar padrões não-lineares, identificando 28 clientes a mais que seriam perdidos em comparação à Regressão Logística.

🔍 3. Insights Estratégicos (Findings)
A análise revelou que o Churn na Telecom X é impulsionado por fatores específicos:

a) ⚠️ O Vilão do Pagamento Manual: Clientes que utilizam boletos ou cheques eletrônicos têm a maior taxa de evasão. A "fricção" do pagamento mensal estimula o cancelamento.
b) 📡 O Risco da Fibra Óptica: Apesar de ser tecnologia de ponta, clientes de fibra apresentam alta rotatividade, indicando necessidade de revisão de preços ou qualidade.
c) 🛡️ O Escudo do Tenure: Clientes com mais de 12-24 meses de casa e contratos de longo prazo são a base de sustentação da empresa e raramente cancelam.

🛠️ 4. Tecnologias e Técnicas Utilizadas
Linguagem: Python
Manipulação de Dados: Pandas, NumPy
Visualização: Matplotlib, Seaborn
Machine Learning: Scikit-Learn (Logistic Regression, Random Forest)
Pré-processamento: One-Hot Encoding (drop_first=True), Min-Max Scaling, SMOTE (Oversampling).

📋 5. Estrutura do Repositório
notebook/: Arquivo .ipynb com a análise completa.
reports/: Gráficos de importância de variáveis e matrizes de confusão.

👤 Identificação
Nome: João Carlos Maiolo
e-mail: joao.c.maiolo@uol.com.br



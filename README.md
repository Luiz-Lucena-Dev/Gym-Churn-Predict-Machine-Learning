📊 Gym Churn Prediction with Machine Learning
🇧🇷 Descrição

Projeto de Machine Learning desenvolvido para prever a probabilidade de evasão (churn) de alunos em uma academia, com base em variáveis comportamentais e contratuais.

O modelo permite identificar alunos com maior risco de saída e analisar o impacto financeiro da evasão, auxiliando na tomada de decisões estratégicas para retenção e aumento da receita.

🇺🇸 Description

Machine Learning project designed to predict customer churn in a gym environment using behavioral and contractual data.

The model identifies high-risk members and estimates the financial impact of churn, supporting data-driven retention strategies.

🎯 Objetivo
Prever quais alunos têm maior probabilidade de churn
Identificar padrões de comportamento relacionados à evasão
Estimar o impacto financeiro da perda de clientes
Simular cenários de redução de churn
📊 Dados Utilizados

O dataset contém informações relevantes sobre os alunos da academia, como:

📅 Frequência semanal
💳 Tipo de plano (mensal, trimestral, anual)
🏋️ Uso de personal trainer
💰 Valor da mensalidade
👤 Sexo
🔁 Status de churn (evasão)
🔍 Análise Exploratória (EDA)

Durante a análise exploratória, foram investigadas relações entre as variáveis e o churn:

Churn por tipo de plano
Churn por frequência semanal
Churn por sexo
Impacto do uso de personal trainer

📌 Principais insights:

Alunos com baixa frequência possuem maior risco de evasão
Planos mensais apresentam maior churn
Clientes sem personal trainer tendem a sair mais
⚙️ Preparação dos Dados
Tratamento de valores categóricos (get_dummies)
Conversão da variável churn para formato numérico (0 e 1)
Remoção de colunas irrelevantes (ex: nome, id)
Separação entre variáveis de entrada (X) e variável alvo (y)
🤖 Modelagem

Foi utilizado o algoritmo:

🌲 Random Forest Classifier
Motivos da escolha:
Bom desempenho em dados tabulares
Capacidade de capturar relações não lineares
Robustez contra overfitting
📈 Avaliação do Modelo

Métricas utilizadas:

Acurácia
Precision
Recall
F1-score
🚨 Identificação de Alunos em Risco

O modelo permite identificar os alunos com maior probabilidade de churn, possibilitando ações como:

Contato proativo
Ofertas personalizadas
Incentivo ao uso de personal trainer
💰 Impacto Financeiro

O projeto calcula:

Receita total da academia
Receita perdida com churn
Percentual de impacto financeiro
📉 Simulação de Cenários

Simulação de redução de churn:

Exemplo: redução de 20% na evasão
Resultado: diminuição significativa na perda de receita
📊 Visualizações

O projeto inclui gráficos como:

Distribuição de churn
Churn por plano (pizza)
Churn por sexo (pizza)
Churn por frequência (barras)
Top 10 alunos com maior risco de evasão
🛠️ Tecnologias Utilizadas
Python
Pandas
Matplotlib
Scikit-learn
Jupyter Notebook
🚀 Como Executar o Projeto
# Clone o repositório
git clone https://github.com/seu-usuario/gym-churn-prediction-machine-learning.git

# Acesse a pasta
cd gym-churn-prediction-machine-learning

# Instale as dependências
pip install -r requirements.txt

# Execute o notebook
jupyter notebook
📌 Próximos Passos
Implementar dashboard interativo (Streamlit ou Power BI)
Testar outros modelos (XGBoost, Logistic Regression)
Deploy do modelo em ambiente web
Atualização com novos dados
🧠 Conclusão

O modelo desenvolvido demonstrou capacidade de identificar padrões relevantes de evasão de alunos.

A análise evidenciou que fatores como frequência e engajamento são determinantes para retenção.

Com base nesses insights, é possível aplicar estratégias mais eficientes para reduzir churn e aumentar a receita da academia.

👨‍💻 Autor

Desenvolvido por Luiz Guilherme
📌 Focado em Dados e Inteligência Artificial

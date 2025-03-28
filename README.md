📞 Projeto: Previsão de Churn em Telecomunicações

📌 Visão Geral
Projeto de Data Science para prever cancelamento de clientes (churn) em operadoras de telecom, com:

Análise exploratória (EDA)

Modelo de machine learning (Random Forest + SHAP)

Dashboard interativo no Looker Studio

Taxa de acerto: 79.8% (baseline)

🛠 Tecnologias Utilizadas
Python: Pandas, Scikit-learn, SHAP

Visualização: Looker Studio, Matplotlib

Versionamento: GitHub

📂 Estrutura do Repositório
/projeto-churn-telecom
│── /data
│   ├── raw/WA_Fn-UseC_-Telco-Customer-Churn.csv  # Dados brutos
│   └── processed/churn_processed.csv              # Dados tratados
│── /notebooks
│   ├── 01_EDA_Churn_Analysis.ipynb               # Análise exploratória
│   └── 02_Churn_Prediction_Model.ipynb           # Modelo ML
│── /docs
│   └── dashboard_looker.pdf                      # Print do dashboard
│── README.md                                     # Este arquivo
└── requirements.txt                              # Dependências

🚀 Como Executar

Pré-requisitos:

Python 3.8+
git clone https://github.com/seu-usuario/projeto-churn-telecom.git
pip install -r requirements.txt

Passo a Passo:

# 1. Rodar análise exploratória
jupyter notebook notebooks/01_EDA_Churn_Analysis.ipynb

# 2. Treinar modelo (incluindo SHAP)
jupyter notebook notebooks/02_Churn_Prediction_Model.ipynb

Acesse o Dashboard:


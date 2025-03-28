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

📁 projeto-churn-telecom/
│

├── 📂 data/

│ ├── 📂 raw/

│ │ └️ 🗄️ WA_Fn-UseC_-Telco-Customer-Churn.csv (dados brutos)

│ └── 📂 processed/

│ ├️ 🗄️ churn_clean.csv

│ └️ 🗄️ churn_encoded.csv (pronto para ML)
│

├── 📂 notebooks/

│ ├️ 📓 01_eda.ipynb (análise exploratória)

│ ├️ 📓 02_model_training.ipynb

│ └️ 📓 03_shap_analysis.ipynb
│

├── 📂 src/

│ ├️ 🐍 preprocessing.py (funções de limpeza)

│ └️ 🐍 visualization.py (gráficos customizados)
│

├── 📂 docs/


│ ├️ 📊 dashboard.pdf (print do Looker Studio)

│ └️ 📝 technical_report.md

│
├── 📜 .gitignore

├── 📜 LICENSE

├── 📜 README.md (você está aqui!)

└── 📜 requirements.txt


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

https://lookerstudio.google.com/reporting/454623c9-c48f-4bfc-b876-9b02ce55b685

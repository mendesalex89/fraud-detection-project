# fraud-detection-project

/fraud-detection-project
│
├── /data
│   ├── raw/                    # Dados brutos originais (não tratados)
│   ├── processed/               # Dados processados e prontos para o modelo
│   └── external/                # Dados externos adicionais (se houver)
│
├── /notebooks
│   ├── 01-data-ingestion.ipynb  # Notebook de ingestão de dados
│   ├── 02-data-visualization.ipynb  # Notebook de visualização de dados
│   ├── 03-data-preprocessing.ipynb  # Notebook de tratamento de dados
│   └── 04-modeling.ipynb        # Notebook de treinamento e avaliação do modelo
│
├── /scripts
│   ├── data_ingestion.py        # Script para ingestão de dados
│   ├── data_visualization.py    # Script para visualização de dados
│   ├── data_preprocessing.py    # Script para tratamento de dados
│   ├── model_training.py        # Script para o treinamento do modelo
│   └── mlflow_tracking.py       # Script para rastreamento com MLflow
│
├── /models                      # Pasta onde os modelos treinados serão salvos
│
├── /reports                     # Relatórios gerados automaticamente, gráficos, resultados
│   └── figures/                 # Gráficos e figuras gerados pelo projeto
│
├── requirements.txt             # Arquivo de dependências Python
├── README.md                    # Explicação do projeto
├── .gitignore                   # Arquivo para ignorar arquivos indesejados no Git
├── mlflow.db                    # Banco de dados do MLflow (se necessário)
└── mlruns/                      # Diretório que armazena os experimentos do MLflow
ns


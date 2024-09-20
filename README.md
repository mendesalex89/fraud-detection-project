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






### Description of Key Folders and Files

- **/data**: Contains datasets for the project.
  - **raw/**: Original data that hasn't been processed.
  - **processed/**: Data that has been cleaned and is ready to be used for modeling.
  - **external/**: Any additional datasets from external sources.

- **/notebooks**: Jupyter notebooks for exploration and step-by-step workflow.
  - **01-data-ingestion.ipynb**: Notebook for ingesting raw data.
  - **02-data-visualization.ipynb**: Data visualization and exploratory analysis.
  - **03-data-preprocessing.ipynb**: Preprocessing and cleaning of data.
  - **04-modeling.ipynb**: Training, evaluation, and model performance metrics.

- **/scripts**: Python scripts for automation and running tasks outside notebooks.
  - **data_ingestion.py**: Script for automating the data ingestion process.
  - **data_visualization.py**: Script to generate data visualizations.
  - **data_preprocessing.py**: Script for cleaning and transforming the dataset.
  - **model_training.py**: Handles training and saving machine learning models.
  - **mlflow_tracking.py**: Sets up and tracks experiments using MLflow.

- **/models**: Trained machine learning models will be saved in this directory.

- **/reports**: Stores reports and results generated during the project.
  - **figures/**: Contains charts and figures created for reports and presentations.

- **requirements.txt**: List of Python dependencies needed to run the project.

- **README.md**: This file, providing an overview and project structure.

- **.gitignore**: Specifies files to be ignored by version control (e.g., large datasets, model files).

- **mlflow.db**: Local SQLite database for MLflow experiment tracking (optional).

- **mlruns/**: Folder that stores MLflow experiment runs.

---

This setup provides an organized structure for reproducibility, model management, and experiment tracking using MLflow. Let me know if you need further adjustments!

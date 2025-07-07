# 20 Newsgroups Dataset

**Dataset Link:** [20 Newsgroups - UCI Machine Learning Repository](http://archive.ics.uci.edu/ml/datasets/Twenty+Newsgroups)

## Setup Instructions

Follow the steps below to set up and run the project:

### 1. Create a virtual environment
```bash
python -m venv news_venv
```

### 2. Activate the virtual environment
```bash
news_venv\Scripts\activate  # For Windows
# source news_venv/bin/activate  # For Linux/Mac
```

### 3. Install dependencies
```bash
pip install -r requirements.txt
```

### 4. Register the environment as a Jupyter kernel
```bash
python -m ipykernel install --user --name=news_venv --display-name="news_venv"
```

### 5. Launch Jupyter Notebook
```bash
jupyter notebook
```

Open the relevant `.ipynb` file and start working with the 20 Newsgroups dataset.

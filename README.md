# 🏈 College Football Analytics

Implementing deep learning techniques to predict college football game outcomes and NFL draft picks using historical data and advanced analytics.

## 📊 Data Sources

- [College Football Data API](https://apinext.collegefootballdata.com)
- [NFL Contract and Draft Dataset](https://www.kaggle.com/datasets/nicholasliusontag/nfl-contract-and-draft-data)

## 🚀 Getting Started

### Prerequisites

- Python 3.8+
- Git
- Conda

### Installation

1. Clone the repository
```bash
git clone https://github.com/KevinDKao/college-football-analytics.git
cd college-football-analytics
```

2. Create and activate Conda environment
```bash
conda create -n cfb-analytics python=3.11
conda activate cfb-analytics
```

3. Install requirements
```bash
pip install -r requirements.txt
```

## 📁 Repository Structure

```
college-football-analytics/
├── 📊 data/                  # Raw and processed data files
│   ├── raw/                  # Original data from sources
│   └── processed/            # Cleaned and transformed data
│
├── 🧪 notebooks/             # Jupyter notebooks for analysis and exploration
│   ├── data_exploration/     # Initial data analysis
│   ├── feature_engineering/  # Feature creation and transformation
│   └── modeling/            # Model development and evaluation
│
├── 🛠️ src/                   # Source code
│   ├── data/                # Data processing scripts
│   ├── features/            # Feature engineering code
│   ├── models/              # Model implementation
│   └── utils/               # Utility functions
│
├── 📈 models/                # Saved model artifacts
│   ├── trained/             # Trained model files
│   └── experiments/         # Experiment tracking
│
├── 📝 docs/                  # Documentation
│   ├── api/                 # API documentation
│   └── reports/             # Analysis reports and findings
│
├── 🧪 tests/                 # Unit tests
├── 📋 requirements.txt       # Project dependencies
├── 🐍 setup.py              # Package setup file
└── 📖 README.md             # This file
```

## 🔑 API Keys

1. Create a `.env` file in the root directory
2. Add your API keys:
```
CFB_API_KEY=your_college_football_api_key
```

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details
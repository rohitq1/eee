
# Machine Learning Project

This repository contains the code and data for a Algebraic Answers Prediction Using MathBERT,GPT-2 & Auto-Tokenizer Embeddings 


## Directory Structure

```
ML_CODES1/
└── ML_CODES/
    └── FINAL/
        └── ML/
            ├── catboost_info/
            ├── DATA_FILES/
            │   ├── Auto.xlsx
            │   ├── GPT2_reordered.xlsx
            │   ├── MathBert.xlsx
            │   └── testing_mathbert.xlsx
            ├── TESTING & LR TRAINING RESULTS.ipynb
            ├── TRAINING-1.ipynb
            ├── TRAINING-3.ipynb
            ├── TRAINING-4.ipynb
            └── TRAINING-2.ipynb
```

## Contents

### Notebooks

- `TESTING & LR TRAINING RESULTS.ipynb`: Contains the testing  and linear regression training results.
- `TRAINING-1.ipynb`: Training of algorithms like KNN REGRESSOR 
- `TRAINING-3.ipynb`: Training of algorithms mainly TREE ALGORTHMS AND BOOSTING 
- `TRAINING-4.ipynb`: Training of CAT BOOST
- `TRANiING-2.ipynb`: Training of algorithms like SVR

### Data Files

- `Auto.xlsx`:Autotokenizer embeddings dataset used for training  .
- `GPT2_reordered.xlsx`: GPT2 embeddings dataset used for training.
- `MathBert.xlsx`:Mathbert embeddings dataset used for training .
- `testing_mathbert.xlsx`: Math bert dataset used for  testing.

### Other Directories

- `catboost_info/`: Directory containing information related to CatBoost training.

## Getting Started

1. Clone the repository:

```sh
git clone <repository_url>
```

2. Navigate to the project directory:

```sh
cd ML_CODES1/ML_CODES/FINAL/ML
```

3. Open the desired Jupyter notebook:

```sh
jupyter notebook <notebook_name>.ipynb
```

4. Run the cells in the notebook to train or test the models using the provided datasets.

## Requirements

- Jupyter Notebook
- Python 3.x
- Required Python packages (listed in the notebooks)

## Notes

- Ensure that all the necessary Python packages are installed before running the notebooks.
- The datasets in the `DATA_FILES` directory are used for training and testing the models in the notebooks.
- Detailed descriptions and explanations are provided within the notebooks.

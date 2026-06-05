# Machine Learning Projects

A collection of practical machine learning projects built with Python and Jupyter Notebook. The projects cover core ML workflows such as data preprocessing, exploratory analysis, model training, hyperparameter tuning, evaluation, visualization, deep learning, image classification, word embeddings, and text classification.

## About This Repository

This repository is organized as a portfolio of machine learning projects. Each notebook focuses on applying machine learning concepts to a specific problem, dataset, or modeling technique. The work includes both classical machine learning methods and deep learning approaches.

## Projects Included

| Project | Notebook | Main Focus | What is Used |
|---|---|---|---|
| Project 1: Breast Cancer Classification | `notebooks/HW1_kNN_DecisionTree_BreastCancer.ipynb` | Classifying tumors as malignant or benign | k-Nearest Neighbors, Decision Tree, feature standardization, validation tuning, confusion matrix, accuracy evaluation |
| Project 2: Machine Learning Fundamentals | `notebooks/HW2_MachineLearning.ipynb` | Working with generated datasets and numerical ML exercises | NumPy, Matplotlib, data generation, mathematical implementation, visualization |
| Project 3: ADALINE and Neural Network Concepts | `notebooks/HW3_Adaline_MLP.ipynb` | Implementing learning algorithms and studying training behavior | ADALINE, mini-batch SGD, momentum, ReLU, binary cross-entropy, NumPy, scikit-learn datasets |
| Project 4: Food Image Classification | `notebooks/HW4_MachineLearning.ipynb` | Building image classification models | PyTorch, Torchvision, CNN concepts, image preprocessing, DataLoader, train/validation split, model training |
| Project 5: Word Embeddings and Text Classification | `notebooks/HW5_WordEmbeddings_GloVe.ipynb` | Working with NLP models and text classification | GloVe embeddings, cosine similarity, nearest neighbors, word analogies, t-SNE visualization, Naive Bayes, CountVectorizer |

## Report

| File | Description |
|---|---|
| `reports/HW1_Report_BreastCancerClassification.pdf` | Written report for the breast cancer classification project, including methodology, preprocessing, model results, confusion matrices, misclassification analysis, and conclusion |

## Technologies and Libraries

This repository uses:

- **Python** for programming and implementation
- **Jupyter Notebook** for experiments, explanations, and visual outputs
- **NumPy** for numerical operations and manual algorithm implementation
- **Pandas** for tabular data handling
- **Matplotlib** for charts and visualizations
- **scikit-learn** for datasets, preprocessing, model training, evaluation, and classical machine learning models
- **PyTorch** and **Torchvision** for deep learning and image classification workflows
- **Pillow** for image processing
- **Gensim** for loading and working with pre-trained GloVe word embeddings

## Main Skills Demonstrated

- Data loading and preprocessing
- Exploratory data analysis
- Feature standardization
- Classification model training
- Hyperparameter tuning using validation data
- Model evaluation using accuracy and confusion matrices
- Manual implementation of learning algorithms using NumPy
- Neural network training concepts
- Image preprocessing and classification with PyTorch
- Natural language processing with word embeddings
- Text classification using bag-of-words features and Naive Bayes
- Visualization of data, results, and embeddings

## Repository Structure

```text
machine-learning-projects/
│
├── README.md
├── requirements.txt
├── .gitignore
├── LICENSE
│
├── notebooks/
│   ├── HW1_kNN_DecisionTree_BreastCancer.ipynb
│   ├── HW2_MachineLearning.ipynb
│   ├── HW3_Adaline_MLP.ipynb
│   ├── HW4_MachineLearning.ipynb
│   └── HW5_WordEmbeddings_GloVe.ipynb
│
└── reports/
    └── HW1_Report_BreastCancerClassification.pdf
```

## How to Run

1. Clone the repository:

```bash
git clone https://github.com/YOUR-USERNAME/machine-learning-projects.git
cd machine-learning-projects
```

2. Install the required packages:

```bash
pip install -r requirements.txt
```

3. Open the notebooks:

```bash
jupyter notebook
```

or:

```bash
jupyter lab
```

## Notes

- Some notebooks may require downloading datasets or external resources before running.
- Some deep learning notebooks are better executed in Google Colab or an environment with GPU support.
- Large datasets, model checkpoints, and virtual environments are intentionally excluded from the repository.

## Contact

**Abdullah Homsi**  
Email: homsiabdullah4@gmail.com  
Phone: +962 79 58787 27

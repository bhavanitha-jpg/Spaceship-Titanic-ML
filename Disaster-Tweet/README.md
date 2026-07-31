# Disaster Tweet Classification using DistilBERT

## 📌 Project Overview

This project focuses on classifying tweets as **real disaster-related** or **non-disaster** using Natural Language Processing (NLP) and Deep Learning. The project includes Exploratory Data Analysis (EDA), text preprocessing, and fine-tuning the DistilBERT transformer model to perform binary text classification.

---

## 🎯 Objectives

- Analyze the disaster tweet dataset using Exploratory Data Analysis (EDA).
- Preprocess textual data for transformer-based models.
- Fine-tune the DistilBERT model for binary classification.
- Evaluate model performance using standard classification metrics.

---

## 📂 Project Structure

```
├── EDA.ipynb                        # Data analysis and visualization
├── DistilBERT_DisasterTweets.ipynb  # Model training and evaluation
├── README.md
└── dataset/
    ├── train.csv
    └── test.csv
```

---

## 📊 Dataset

The project uses the **Natural Language Processing with Disaster Tweets** dataset.

Each record contains:

- **id** – Unique tweet identifier
- **keyword** – Disaster-related keyword
- **location** – User location (optional)
- **text** – Tweet content
- **target** – Label
  - 0 → Not a disaster tweet
  - 1 → Real disaster tweet

---

## 🔍 Exploratory Data Analysis (EDA)

The EDA notebook includes:

- Dataset overview
- Missing value analysis
- Class distribution
- Tweet length analysis
- Word frequency analysis
- Data visualization
- Basic text cleaning

---

## ⚙️ Data Preprocessing

The preprocessing pipeline includes:

- Lowercase conversion
- Removal of URLs
- Removal of special characters
- Tokenization using DistilBERT Tokenizer
- Padding and truncation
- Attention mask generation

---

## 🤖 Model

The project uses **DistilBERT**, a lightweight version of BERT developed by Hugging Face.

### Model Features

- Pre-trained Transformer Architecture
- Context-aware text embeddings
- Fine-tuned for binary text classification
- Faster training than BERT while maintaining high accuracy

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- PyTorch
- Hugging Face Transformers
- Google Colab / Jupyter Notebook

---

## 📈 Model Evaluation

The trained model is evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

---

## 🚀 How to Run

### 1. Clone Repository

```bash
git clone https://github.com/yourusername/disaster-tweet-classification.git
cd disaster-tweet-classification
```

### 2. Install Dependencies

```bash
pip install -r requirements.txt
```

or

```bash
pip install transformers torch datasets pandas numpy matplotlib seaborn scikit-learn
```

### 3. Run the Notebooks

Open Jupyter Notebook or Google Colab and execute:

1. `EDA.ipynb`
2. `DistilBERT_DisasterTweets.ipynb`

---

## 📌 Workflow

```
Dataset
     │
     ▼
Exploratory Data Analysis
     │
     ▼
Text Cleaning
     │
     ▼
Tokenization
     │
     ▼
DistilBERT Fine-Tuning
     │
     ▼
Prediction
     │
     ▼
Performance Evaluation
```

---

## 📚 Future Improvements

- Hyperparameter tuning
- Data augmentation
- Cross-validation
- Deploy using Streamlit or Flask
- Compare DistilBERT with BERT, RoBERTa, and ALBERT

---

## 👩‍💻 Author

**Bhavanitha**

Final Year B.Tech CSE (Artificial Intelligence & Machine Learning)

Aspiring AI/ML Engineer | Machine Learning | Deep Learning | Natural Language Processing

---

## 📄 License

This project is developed for educational and research purposes.
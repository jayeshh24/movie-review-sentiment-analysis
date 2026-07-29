# 🎬 IMDB Movie Review Sentiment Analysis Using Deep Learning

## 📌 Project Overview
This project is a Deep Learning-based sentiment analysis system that classifies IMDB movie reviews as either **Positive** or **Negative**. It uses Natural Language Processing (NLP) techniques for text preprocessing and a trained deep learning model to accurately predict the sentiment of movie reviews.

---

## 🚀 Features
- Predicts the sentiment of IMDB movie reviews.
- Classifies reviews as **Positive** or **Negative**.
- Text preprocessing using tokenization and padding.
- Deep Learning model built using TensorFlow/Keras.
- Simple and easy-to-use Jupyter Notebook implementation.

---

## 🛠️ Technologies Used
- Python
- TensorFlow / Keras
- NumPy
- Pandas
- Scikit-learn
- Pickle
- Jupyter Notebook

---

## 📂 Project Structure

```text
movie-review/
│── phase1.ipynb
│── model evaluation.ipynb
│── model.h5
│── tokenizer.pkl
│── README.md
└── requirements.txt
```

---

## 📊 Dataset

This project uses the **IMDB Dataset of 50K Movie Reviews**.

The dataset is not included in this repository because of GitHub's file size limitations.

### Download the Dataset

Download the dataset from Kaggle:

https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews

### Setup

1. Download the dataset.
2. Rename the downloaded file (if necessary) to **`IMDB Dataset.csv`**.
3. Place the file in the project root directory (the same folder as `phase1.ipynb`).

The project structure should look like this:

```text
movie-review/
│── IMDB Dataset.csv
│── phase1.ipynb
│── model evaluation.ipynb
│── model.h5
│── tokenizer.pkl
│── README.md
└── requirements.txt
```

> **Note:** The notebook loads the dataset using:
>
> ```python
> pd.read_csv("IMDB Dataset.csv")
> ```
>
> Therefore, the dataset file must be placed in the project root directory.

---

## ▶️ How to Run

1. Clone this repository.

2. Install the required libraries:

```bash
pip install -r requirements.txt
```

3. Download the dataset from Kaggle.

4. Place **`IMDB Dataset.csv`** in the project root directory.

5. Open **`phase1.ipynb`** in Jupyter Notebook.

6. Run all the cells.

---

## 📈 Output

The model predicts whether a movie review is:

- ✅ Positive
- ❌ Negative

---

## 📌 Future Improvements

- Develop a web application using Flask or FastAPI.
- Improve model accuracy using advanced deep learning architectures.
- Deploy the model on cloud platforms.
- Add real-time sentiment prediction through a user-friendly interface.

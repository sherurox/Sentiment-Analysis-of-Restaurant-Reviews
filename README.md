# Sentiment Analysis of Restaurant Reviews

## 📌 Project Overview
This project applies **Natural Language Processing (NLP)** techniques to classify restaurant reviews as **positive** or **negative** using machine learning models. The dataset contains customer reviews, which are processed and analyzed to determine sentiment.

## 📂 Repository Structure
```
📦 Sentiment-Analysis-Restaurant-Reviews
 ┣ 📜 Sentiment Analysis of Restaurant Reviews.ipynb  # Jupyter Notebook with complete code
 ┣ 📜 Restaurant_Reviews.tsv                          # Dataset containing restaurant reviews
 ┣ 📜 README.md                                      # Project documentation
```

## 📊 Dataset Description
- The dataset is stored in a **TSV (Tab-Separated Values)** file: `Restaurant_Reviews.tsv`.
- It consists of restaurant reviews along with their sentiment labels (positive/negative).

## 🛠️ Technologies & Libraries Used
- **Programming Language**: Python
- **Libraries Used**:
  - `pandas` – Data manipulation
  - `numpy` – Numerical operations
  - `nltk` – Natural Language Processing
  - `re` – Regular Expressions for text cleaning
  - `sklearn` – Machine Learning models

## 📌 Project Workflow
### 1️⃣ Data Preprocessing
- Load dataset from `Restaurant_Reviews.tsv`
- Clean text:
  - Remove special characters
  - Convert text to lowercase
  - Tokenize words
  - Remove stopwords
  - Apply stemming
- Store cleaned text in a **corpus**.

### 2️⃣ Feature Extraction
- Use `CountVectorizer` to convert text into a **Bag-of-Words** model.

### 3️⃣ Model Training
- Train a **Machine Learning classifier** (e.g., Naïve Bayes, Logistic Regression, or SVM) on the processed text.
- Split dataset into **training and testing sets**.

### 4️⃣ Model Evaluation
- Predict sentiment on test data.
- Evaluate using:
  - Accuracy Score
  - Precision, Recall, and F1-score
  - Confusion Matrix

## 🚀 How to Run the Project
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/Sentiment-Analysis-Restaurant-Reviews.git
   cd Sentiment-Analysis-Restaurant-Reviews
   ```
2. **Install Dependencies**:
   ```bash
   pip install pandas numpy nltk scikit-learn
   ```
3. **Run the Jupyter Notebook**:
   ```bash
   jupyter notebook "Sentiment Analysis of Restaurant Reviews.ipynb"
   ```

## 📈 Results & Insights
- The trained model is capable of distinguishing between **positive** and **negative** restaurant reviews with high accuracy.
- The sentiment analysis can help businesses understand customer feedback and improve services.

## 🤝 Contributing
Feel free to fork the repository and submit **pull requests** for improvements.

## 📜 License
This project is licensed under the **MIT License**.

## Authors & Acknowledgments
Shreyas Khandale (https://github.com/sherurox) <br>
Rohan Patil (https://github.com/rohanpatil2) <br>

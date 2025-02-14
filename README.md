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
![image](https://github.com/user-attachments/assets/f6007102-5ba0-43b6-93bb-5fe0415dd5ee)


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
- Train a **Naïve Bayes classifier** with **hyperparameter tuning**.
- Split dataset into **training and testing sets**.

### 4️⃣ Model Evaluation
- Predict sentiment on test data.
- Evaluate using:
  - Accuracy Score
  - Precision, Recall, and F1-score
  - Confusion Matrix

## 📊 Model Performance Results
| Metric                  | Value |
|-------------------------|-------|
| **Best Accuracy Score** | **85.5%** |
| **Optimal Alpha Value** | **0.2** |
| **Confusion Matrix**    | See below |

### **Confusion Matrix**
|                   | Predicted Negative | Predicted Positive |
|-------------------|-------------------|-------------------|
| **Actual Negative** | 76 | 21 |
| **Actual Positive** | 18 | 85 |

### **Hyperparameter Tuning Results (Naïve Bayes Alpha Parameter)**
| Alpha (α) Value | Accuracy (%) |
|----------------|-------------|
| 0.1 | 84.0% |
| 0.2 | 85.5% |
| 0.3 | 84.8% |
| 0.4 | 84.2% |
| 0.5 | 83.9% |
| 0.6 | 83.5% |
| 0.7 | 83.1% |
| 0.8 | 82.7% |
| 0.9 | 82.4% |
| 1.0 | 82.0% |
![image](https://github.com/user-attachments/assets/6bf02b0f-2632-486f-b872-99dcf7cdb9e3)


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

## Authors & Acknowledgments
Shreyas Khandale (https://github.com/sherurox) <br>
Rohan Patil (https://github.com/rohanpatil2) <be>

## 📜 License
This project is licensed under the **MIT License**.

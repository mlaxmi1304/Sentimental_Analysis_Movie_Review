# Sentiment Analysis on IMDB Movie Reviews

## 📑 Project Overview  
This project performs sentiment analysis on IMDB movie reviews using Natural Language Processing (NLP) techniques and machine learning algorithms. The objective is to classify reviews as positive or negative based on textual data.

## 🎯 Objectives  
- Clean and preprocess text data from IMDB reviews.
- Train multiple machine learning models for sentiment classification.
- Compare the performance of different models.

## 🛠️ Tools and Technologies Used  
- **Programming Language:** Python  
- **Libraries:** Pandas, NLTK, Scikit-learn, Regular Expressions  
- **Algorithms:**  
  - Gaussian Naive Bayes  
  - Multinomial Naive Bayes  
  - Bernoulli Naive Bayes  
  - Random Forest Classifier  
  - Logistic Regression  

## 🚀 How to Run the Project  

1. **Download the project**  
   If you haven't cloned the repository using Git, you can download the ZIP file from GitHub:  
   [Download ZIP](https://github.com/mlaxmi1304/Sentimental_Analysis_Movie_Review)

   After downloading, extract the ZIP file to a directory of your choice.

2. **Navigate to the project directory:**  
   Open your terminal or command prompt and navigate to the project directory where you extracted the files. For example:
   ```bash
   cd path/to/Sentimental_Analysis_Movie_Review
   ```

3. **Install the required dependencies:**  
   Run the following command to install the necessary Python libraries:
   ```bash
   pip install pandas nltk scikit-learn
   ```

4. **Download NLTK stopwords data (if not already downloaded):**  
   Run this Python code to download NLTK stopwords:
   ```python
   import nltk
   nltk.download('stopwords')
   ```

5. **Ensure the dataset `IMDB-Dataset.csv` is in the working directory.**

6. **Run the Jupyter notebook**  
   If you're using Jupyter Notebook, launch it with the following command:
   ```bash
   jupyter notebook
   ```
   Then, open the `sentiment_analysis.ipynb` file and run the cells. Alternatively, if you have a `.py` file, run it by executing:
   ```bash
   python sentiment_analysis.py
   ```

## 📂 Project Structure  
```
Sentiment-Analysis/
├── IMDB-Dataset.csv       # Dataset of IMDB reviews
├── sentiment_analysis.py   # Main code file for analysis (or sentiment_analysis.ipynb for Jupyter Notebook)
└── README.md               # Project documentation
```

## 📂 Dataset
The dataset used for sentiment analysis is the [IMDB Dataset](https://raw.githubusercontent.com/mlaxmi1304/Sentimental_Analysis_Movie_Review/main/IMDB-Dataset.csv).  
You can download the dataset from this link and place it in your project directory.


## 📊 Key Steps in Analysis  
- **Data Preprocessing:**  
  - Removal of HTML tags  
  - Lowercasing and tokenization  
  - Stopword removal and stemming  
- **Vectorization:**  
  - TF-IDF vectorization  
- **Model Training and Evaluation:**  
  - Gaussian, Multinomial, and Bernoulli Naive Bayes  
  - Random Forest Classifier  
  - Logistic Regression  

## 📈 Model Comparison  
| Algorithm                 | Accuracy   |
|---------------------------|------------|
| Gaussian Naive Bayes      | *74%*      |
| Multinomial Naive Bayes   | *85%*      |
| Bernoulli Naive Bayes     | *84%*      |
| Random Forest Classifier  | *84%*      |
| Logistic Regression       | *86%*      |

## 🙌 Contributions  
Contributions are welcome! Feel free to fork the repository and submit a pull request.

## 📧 Contact  
For any questions or suggestions, please contact at mahalaxmipandey2004@gmail.com.

---


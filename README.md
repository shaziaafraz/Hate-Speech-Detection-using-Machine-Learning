 Hate Speech Detection using Machine Learning  
  Introduction
Social media generates an enormous amount of text data every second. Unfortunately, a portion of this content contains ""hate speech"" or ""offensive language"", which can harm individuals and communities.  
This project focuses on building a ""machine learning model"" to automatically classify text into categories such as Hate Speech, Offensive Language, or No Hate/Offensive Content.  

The goal of this project is to demonstrate how Natural Language Processing (NLP) and machine learning techniques can be applied to detect harmful content online and contribute to safer digital communication.  

---

 Dataset
- Dataset used: "labeled tweets" containing three classes:  
  - 0 → Hate Speech  
  - 1 → Offensive Language  
  - 2 → No Hate or Offensive Language  
- File used: 'labeled_data.csv' 

---

Technologies & Libraries Used
- Programming Language: Python  
- Libraries:  
  - 'pandas', 'numpy' → Data handling  
  - 'nltk' → Stopwords removal, stemming, text preprocessing  
  - 'scikit-learn' → CountVectorizer, train-test split, Decision Tree Classifier, evaluation  
  - 'matplotlib', 'seaborn' → Visualization (confusion matrix heatmap)  

---

🔎 Project Workflow
1. Data Loading & Exploration  
   - Loaded dataset, checked for null values, explored basic statistics.  

2. Preprocessing 
   - Lowercasing text  
   - Removing URLs, HTML tags, special characters & punctuation  
   - Stopword removal  
   - Word stemming  

3. Feature Engineering
   - Used ""CountVectorizer (Bag-of-Words model)"" to transform text into numerical features.  

4. Model Training
   - Trained a ""Decision Tree Classifier"" using Scikit-learn.  

5. Evaluation
   - Evaluated model using ""Confusion Matrix"" and ""Accuracy Score"".  
   - Visualized results with Seaborn heatmap.  

6. Prediction Example 
   - Tested the model on a custom input sample 


 Results
- The model achieved a reasonable accuracy score (0.8917960630883971).  
- Confusion Matrix visualized classification performance across 3 categories.  

 How to Run This Project
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/hate-speech-detection.git
   cd hate-speech-detection
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the notebook:
   ```bash
   jupyter notebook "Hate speech detection.ipynb"
   ```

---
 Author
- SHAZIA AFRAZ 
- Project on Hate Speech Detection  
- GitHub: [username-shaziaafraz](https://github.com/shaziaafraz)  

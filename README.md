
# NLP Assignment 1: Text Preprocessing and Tokenization

This repository contains the solution for **NLP Assignment 1**, which involves text preprocessing, tokenization, and frequency analysis using three popular NLP libraries: **NLTK**, **TextBlob**, and **spaCy**. The assignment compares their runtime performances and outputs tokenized sentences, tokenized words, and the top 10 most common words.

---

## **Contents**

### **Code Notebook**
The implementation is available as a Kaggle notebook. You can view or download the notebook using the following link:

- [Kaggle Notebook](https://www.kaggle.com/code/pawaritdilokwuttisit/nlp-assignment1)

### **Input File**
- **`aliced29.txt`**: Input text file used for text preprocessing and analysis.

### **Output Files**
The notebook generates the following output files:
1. **`cleaned.txt`**: Contains the cleaned version of the input text.
2. **`words.txt`**: Contains tokenized words after removing stopwords.
3. **`words_sentences.txt`**: Contains both tokenized sentences and tokenized words.
4. **`top10words.txt`**: Contains the top 10 most frequent words and their frequencies.
5. **`time_compares.txt`**: Contains the runtime comparison of NLTK, TextBlob, and spaCy.

---

## **Instructions to Run**

### **Option 1: Run Directly in Kaggle**
1. Open the Kaggle notebook link: [Kaggle Notebook](https://www.kaggle.com/code/pawaritdilokwuttisit/nlp-assignment1).
2. Add the input file (`aliced29.txt`) to the Kaggle dataset.
3. Run the notebook cells to generate the outputs.

### **Option 2: Run Locally**
1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/your-username/your-repository-name.git
   cd your-repository-name
   ```
2. Install the required libraries:
   ```bash
   pip install nltk textblob spacy
   python -m spacy download en_core_web_sm
   ```
3. Run the notebook using Jupyter Notebook: Start Jupyter Notebook in your terminal and open the nlp-assignment1.ipynb file:
   ```bash
   jupyter notebook
   ```
4. Execute the cells: Run the cells in the notebook sequentially to generate the outputs.

5. View the generated output files: The output files (cleaned.txt, words.txt, words_sentences.txt, top10words.txt, and time_compares.txt) will be saved in the working directory.

---

## **External Libraries Used**
The following libraries are required to run the scripts:
- **NLTK**:
  - For text preprocessing, tokenization, and stopword removal.
- **TextBlob**:
  - For text tokenization and basic NLP tasks.
- **spaCy**:
  - For advanced NLP processing and tokenization.

---

## **Runtime Comparisons**
NLTK, TextBlob, and spaCy runtimes are recorded in the `time_compares_summary.txt` file. These times can be compared to evaluate each library's performance for text preprocessing.


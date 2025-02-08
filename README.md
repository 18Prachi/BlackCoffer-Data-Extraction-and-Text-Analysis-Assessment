# 📝 BlackCoffer Data Extraction & NLP Analysis

This project focuses on **extracting textual data** from given URLs and performing **text analysis** to compute various linguistic variables.

## 🚀 Objective
The goal is to:
1. Extract article text from URLs provided in `Input.xlsx`.
2. Perform text analysis and compute variables as per `Output Data Structure.xlsx`.
3. Save the extracted text and analyzed output in the required format.

## 📌 Data Extraction
- **Input**: URLs provided in `Input.xlsx`
- **Output**: Extracted article text stored in text files (`URL_ID.txt`)
- **Requirements**:
  - Extract only the **article title** and **article text** (exclude headers, footers, etc.).
  - Use **Python** with libraries like:
    - `BeautifulSoup`
    - `Selenium`
    - `Scrapy`
    - Any other preferred web scraping tool.

## 📊 Text Analysis
For each extracted text, compute the following **linguistic variables** as per `Text Analysis.docx`:
- **POSITIVE SCORE**
- **NEGATIVE SCORE**
- **POLARITY SCORE**
- **SUBJECTIVITY SCORE**
- **AVG SENTENCE LENGTH**
- **PERCENTAGE OF COMPLEX WORDS**
- **FOG INDEX**
- **AVG NUMBER OF WORDS PER SENTENCE**
- **COMPLEX WORD COUNT**
- **WORD COUNT**
- **SYLLABLE PER WORD**
- **PERSONAL PRONOUNS**
- **AVG WORD LENGTH**

## 📁 Output Format
- The output should be stored in a CSV/Excel file structured as per `Output Data Structure.xlsx`.

## 📖 Instructions & Approach

### **🔹 How We Approached the Solution**
1. **Data Extraction**:
   - Read URLs from `Input.xlsx`.
   - Used web scraping techniques with `BeautifulSoup`
   - Stored extracted text in `.txt` files named after `URL_ID`.

2. **Text Analysis**:
   - Processed the extracted text using `NLTK` and `TextBlob`.
   - Computed required linguistic variables, including:
     - **Sentiment Scores** (Positive, Negative, Polarity, Subjectivity)
     - **Readability Metrics** (Fog Index, Complex Word Percentage)
     - **Text Structure** (Word Count, Syllables, Sentence Length)
   - Saved results in `Output Data Structure.xlsx` format.

3. **Final Output**:
   - Ensured the **output format matched exactly** as per `Output Data Structure.xlsx`.
   - Provided an easy-to-run **Python script** with clear execution steps.

---

## 🛠️ How to Run the `.py` File
### **1️⃣ Install Dependencies**
Ensure you have Python installed, then install :
```bash
pip install beautifulsoup4




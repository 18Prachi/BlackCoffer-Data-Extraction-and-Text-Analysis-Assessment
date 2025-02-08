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

## 🛠️ Setup & Execution
### **1️⃣ Install Dependencies**
Ensure you have Python installed, then install required librarie:
```bash
pip install beautifulsoup4


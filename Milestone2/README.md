# Employee Wellness Management Analytics - Milestone 2

## Project Objective

The objective of this milestone is to build a robust Natural Language Processing (NLP) Text Preprocessing Pipeline that prepares multilingual employee feedback text for sentiment and emotion analysis.

---

## NLP Pipeline Overview

The system accepts text input directly or through uploaded TXT and CSV files. It then preprocesses the text through multiple stages such as language detection, cleaning, tokenization, stopword removal, and lemmatization before preparing it for further sentiment and emotion analysis.

---

## Technologies and Libraries Used

### Technologies

* Python
* Google Colaboratory
* Streamlit
* FastAPI
* GitHub

### Libraries

* NLTK
* Pandas
* Regex (re)
* LangDetect
* Emoji
* Unicodedata
* SpaCy

---

## Google Colab Setup Instructions

Install required libraries:

```python
!pip install nltk
!pip install langdetect
!pip install emoji
!pip install pandas
!pip install spacy
```

Run all notebook cells sequentially.

---

## Preprocessing Workflow

Input Text
↓
Language Detection
↓
Unicode Normalization
↓
Text Cleaning
↓
URL Removal
↓
Email Removal
↓
HTML Tag Removal
↓
Emoji Extraction and Removal
↓
Punctuation and Number Removal
↓
Lowercase Conversion
↓
Tokenization
↓
Stopword Removal
↓
Lemmatization
↓
Final Preprocessed Text

---

## Features Implemented

* Direct Text Input
* TXT File Upload Support
* CSV File Upload Support
* Multilingual Language Detection
* Unicode Text Normalization
* Text Cleaning
* URL and Email Removal
* HTML Tag Removal
* Emoji Extraction
* Tokenization
* Stopword Removal
* Lemmatization
* Sentiment Analysis
* Emotion Analysis
* Intermediate Output Display

---

## Sample Input

```text
నాకు ఈ మధ్య చాలా ఒత్తిడిగా అనిపిస్తోంది 😔
```

---

## Sample Output

Detected Language: Telugu (te)

Extracted Emoji:
😔

Tokens:
['నాకు', 'ఈ', 'మధ్య', 'చాలా', 'ఒత్తిడిగా', 'అనిపిస్తోంది']

Final Preprocessed Text:
ఒత్తిడిగా అనిపిస్తోంది

Sentiment:
Negative

Emotion:
Sad

---

## Screenshots

The Screenshots folder contains images demonstrating:

* Login Page
* Home Page
* File Upload
* Language Detection
* NLP Preprocessing Outputs
* Sentiment Analysis
* Emotion Analysis
* Processing Statistics

---

## Observations

* The system successfully preprocesses multilingual text.
* Emoji extraction improves emotion understanding.
* Noise removal significantly improves text quality.
* The preprocessing pipeline serves as a foundation for downstream sentiment and emotion classification models.

---

## Folder Structure

```text
Milestone2/
├── NLP_Preprocessing_Pipeline.ipynb
├── README.md
└── Screenshots/
```

## Conclusion

This milestone successfully implements a complete multilingual NLP preprocessing pipeline capable of transforming raw employee feedback into structured text suitable for sentiment and emotion analysis.

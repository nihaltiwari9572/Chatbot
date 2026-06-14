# Chatbot

[README.md](https://github.com/user-attachments/files/28923338/README.md)
# Nehal — FAQ Chatbot
**CodeAlpha AI Internship | Task 2**

## Project Overview
Nehal is an NLP-powered FAQ chatbot that matches user questions to the most relevant FAQ entry using TF-IDF vectorization and cosine similarity.

## Tech Stack
| Component | Tool |
|-----------|------|
| Tokenization | NLTK `word_tokenize` |
| Stopword Removal | NLTK `stopwords` corpus |
| Vectorization | Custom TF-IDF engine |
| Matching | Cosine Similarity |
| UI | Interactive HTML + Vanilla JS |

## NLP Pipeline
```
User Input
   → Lowercase + Remove punctuation
   → NLTK Tokenize
   → Remove stopwords
   → TF-IDF vector
   → Cosine similarity vs all FAQ vectors
   → Best match + confidence score
```

## Project Structure
```
nehal_chatbot/
├── nehal_chatbot.py    # Core NLP engine + CLI
├── requirements.txt    # Dependencies
└── README.md
```

## How to Run
```bash
pip install -r requirements.txt
python nehal_chatbot.py
```

## Features
- Multi-topic FAQ support (E-commerce, Banking, Tech, HR)
- Confidence score with match percentage
- Suggestions for related questions
- Topic switching at runtime
- Low-confidence fallback handling

## Author
Nehal | CodeAlpha Task 2

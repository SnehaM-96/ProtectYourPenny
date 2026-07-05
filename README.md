# Protect Your Penny

> AI-powered Financial News Verification & Scam Intelligence Platform

Protect Your Penny is an AI-powered platform that verifies the authenticity of financial news articles using Natural Language Processing (NLP), semantic similarity search, and explainable AI techniques.

Instead of simply labeling news as *fake* or *real*, the platform compares submitted content with trusted financial sources, explains why the content is suspicious, and presents the closest verified article for comparison.

---

## Project Objectives

- Detect misleading financial news
- Identify common financial scam patterns
- Compare claims with trusted financial sources
- Provide explainable verification
- Continuously update the trusted knowledge base
- Monitor verification trends through Power BI

---

# Key Features

### User Verification Portal

- Paste News
- Enter Article URL
- Upload Text File (.txt)

### AI Verification Report

- Genuineness Score
- Threat Level
- Scam Category
- Why? (Maximum 2 reasons)
- Correct Information
- Closest Trusted Article
- Verify at Source
- Similar Articles
- Processing Timeline

### Knowledge Base

- Daily automatic updates
- Trusted financial sources
- Duplicate detection
- Incremental FAISS updates

### Admin Analytics

Power BI dashboard including:

- Verification statistics
- Scam trends
- Source reliability
- Model performance
- Usage analytics

---

# System Architecture

```
React Frontend
      │
      ▼
Flask REST API
      │
      ▼
Verification Pipeline
      │
 ├── NLP Preprocessing
 ├── Semantic Search
 ├── Scam Classification
 └── Knowledge Base
      │
      ▼
SQLite Database
      │
      ▼
Power BI Dashboard
```

---

# Technology Stack

## Frontend

- React
- Vite
- Tailwind CSS
- shadcn/ui
- Framer Motion
- Axios

## Backend

- Flask
- Flask-CORS
- Python 3.13

## AI & NLP

- spaCy
- NLTK
- Sentence Transformers
- FAISS
- Scikit-learn
- Pandas
- NumPy

## Data Collection

- BeautifulSoup
- Playwright
- APScheduler

## Database

- SQLite

## Analytics

- Power BI

---

# Project Structure

```text
ProtectYourPenny/
│
├── backend/
├── frontend/
├── data/
├── docs/
├── logs/
├── models/
├── scripts/
├── tests/
└── README.md
```

---

# Development Roadmap

- [ ] Project Planning
- [ ] System Design
- [ ] Repository Setup
- [ ] Folder Structure
- [ ] React Frontend
- [ ] Flask Backend
- [ ] NLP Pipeline
- [ ] Semantic Retrieval
- [ ] Scam Classification
- [ ] Knowledge Base
- [ ] Scheduler
- [ ] Power BI Dashboard
- [ ] Deployment

---



## License

MIT License
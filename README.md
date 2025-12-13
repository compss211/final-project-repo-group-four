# COMPSS-211-Final-Project-Team-Four
# **Lyrics, Sentiment, and Theme Evolution in Billboard Top 100 Songs (1959–2023)**

This repository contains the full workflow, analysis, and outputs for our COMPSCI-211 Final Project.  
We study how the lyrics of Billboard Year-End Top 100 songs have evolved over six decades—focusing on **sentiment**, **linguistic patterns**, and **dominant themes** using VADER and BERTopic.

---

## 📁 **Repository Structure**

### **data/**
Contains all raw and processed datasets used in the project.
- `all_songs_data.csv` — Original dataset from Kaggle  
- `all_songs_data_processed.csv` — Kaggle’s partially cleaned file with POS tags  
- `clean_processed.csv` — Our final cleaned dataset for analysis  

---

### **notebooks/**
Jupyter notebooks documenting the full workflow.

#### Data Preparation & Statistics  
- `cleaning.ipynb` — Data filtering, preprocessing, type standardization  
- `descriptive_statistics.ipynb` — Word counts, lexical diversity, linguistic trends  

#### Sentiment Analysis  
- `sentiment_all_decades.ipynb` — Sentiment analysis (VADER) for 1960s–2010s  
- `sentiment_1960s.ipynb` — Additional decade-level exploration  

#### Topic Modeling  
- `general_topics.ipynb` — BERTopic modeling on the full dataset  
- `general_topics_trend.ipynb` — Topic trends by year  
- `bert60s.ipynb`, `1970s_topic.ipynb`, `bert80s.ipynb`, `1990s_topic.ipynb`, `bert00s.ipynb`, `2010s_topic.ipynb` — Deep dives into representative decades  

---

### **Outputs/**
All final figures used in the report and presentation:
- `sentiment_general.png` — Sentiment trends over time  
- `love_negative_positive.png` — Positive vs. negative love themes  
- `main_themes.png` — Distribution of major themes  
- `intertopic_distance(general).png` — BERTopic intertopic distance map  
- `1970s_topics.png` — Example decade-level topic visualization  

---

### **src/Lyrics_data_analyzer/**
Reusable Python modules for helper functions.
- `mymodule.py` — Topic processing / cleaning helpers  
- `utils.py` — Utility functions  
Used to keep notebooks clean and modular.

---

### **scripts/**
Contains small demo or test scripts (not required for the final project).
- `hello_Amy.py`  
- `hello_jazmine.py`  

---
## 🧩 Division of Responsibility

While all major analytical decisions, coding tasks, and interpretations were completed collaboratively, we divided some components of the project to ensure balanced workload and deeper exploration within each decade.

### **Coding & Analysis**
Most technical work—including data cleaning, sentiment analysis, BERTopic modeling, and visualization—was conducted together. We frequently cross-checked one another’s results to ensure reproducibility and consistency.

### **Historical Research by Decade**
To contextualize theme and sentiment patterns, each member investigated the cultural background of specific decades:
- **Amy:** 1970s, 1990s, 2010s  
- **Jazmine:** 1960s, 1980s, 2000s  

These assignments informed our interpretation of decade-specific topic trends and representative songs.

### **Team Workflow**
We met at least once a week (and often twice during heavier stages) to review progress, debug analyses, and jointly interpret results. Even when tasks were initially divided, all outputs were ultimately refined and revised together.



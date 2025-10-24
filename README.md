# 🌍 United Nations Debate Analysis using NLP

### 👨‍💻 By: Khurram Rashid

---

## 📘 Overview
This project applies **Natural Language Processing (NLP)** techniques to analyze speeches from the **United Nations General Assembly Debate Dataset**.  
The goal is to extract meaningful information about world leaders, initiatives, and relations between entities based on their speeches and mentions during UN debates.

---

## 🧠 Objectives
- Identify **mentions of the President** or other global leaders.  
- Extract **mentions of initiatives**, organizations, and countries.  
- Perform **relation extraction** between entities (e.g., *“President → announced → initiative”*).  
- Explore the linguistic structure of political statements using **dependency parsing** and **NER**.  
- Derive insights on **international collaboration themes** and **global issues** discussed.

---

## ⚙️ Tech Stack
| Category | Tools / Libraries |
|-----------|-------------------|
| **Language** | Python |
| **Data Analysis** | Pandas, NumPy |
| **Text Processing** | spaCy, Regex, NLTK |
| **Visualization** | Matplotlib |
| **NLP Tasks** | Tokenization, NER, Dependency Parsing, Relation Extraction |
| **Environment** | Jupyter Notebook / Google Colab |

---

## 🧩 Key NLP Tasks
- **Text Cleaning:** Removed punctuation, symbols, and non-textual elements.  
- **Entity Extraction:** Identified named entities such as `PERSON`, `ORG`, `GPE`, and `DATE`.  
- **Relation Extraction:** Derived relations like  
  - `President → launched → initiative`  
  - `Country → supported → resolution`  
- **Frequency Analysis:** Found the most mentioned countries, leaders, and organizations.  
- **Keyword Contexts:** Extracted phrases using prepositions (`in`, `for`, `by`, `with`) for contextual understanding.

---

## 📊 Example Insights
| Insight | Example |
|----------|----------|
| Most Mentioned Leader | President of the United States |
| Frequent Entities | United Nations, Climate Change, Human Rights |
| Common Relations | “President → urged → nations” |
| Thematic Focus | Peacekeeping, Sustainable Development, Global Cooperation |

---

## 🚀 How to Run
```bash
git clone https://github.com/KhurramRashid/UN-Debate-Analysis.git
cd UN-Debate-Analysis
pip install -r requirements.txt
jupyter notebook

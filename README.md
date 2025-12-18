#  Topic Modelling and Trend Evaluation in Pakistani News

##  Project Description
This project applies **topic modeling and trend analysis** techniques to a large-scale Pakistani news dataset to uncover dominant themes and analyze how news coverage evolves over time. Articles from multiple major news outlets are standardized and analyzed to enable **cross-source comparison** rather than isolated outlet analysis.

The focus is on **National** and **World** news categories from **2020–2023**.

---

## Dataset
### Sources
- Pakistan Today  
- Daily Times  
- Express Tribune  
- Dawn  
- Business Recorder  

### Summary
- **Time Period:** 2020–2023  
- **Total Articles:** 288,150  
- **Categories Used:** National, World  
- **File:** `combined_dataset.csv`

### Key Columns
- `headline` – News article title  
- `date` – Publication date  
- `source` – News outlet  
- `description` – Full article content  
- `mapped_categories` – Standardized category labels  

---

##  Tech Stack
- **Language:** Python  
- **Libraries:** Pandas, NumPy, NLTK, Scikit-learn  
- **Visualization:** Matplotlib, Seaborn  
- **Environment:** Jupyter Notebook  

---

##  Data Processing
- Standardization of heterogeneous category labels  
- Filtering to National and World news  
- Chunk-based processing for large datasets  
- Text cleaning and normalization  
- Encoding handling using Latin-1  

---

##  Methodology
1. Merge and standardize news articles from multiple sources  
2. Preprocess textual data for consistency  
3. Perform exploratory data analysis (EDA)  
4. Apply topic modeling to extract latent themes  
5. Analyze temporal trends across years  
6. Compare topic distributions across news outlets 

---

## Key Insights
- News coverage varies significantly across outlets  
- National news dominates overall reporting  
- Headlines are generally short and concise  
- Sentiment analysis reflects both crisis-driven and optimistic narratives  
- Topic trends change notably over time  

---

## Use Cases
- News trend analysis  
- Media discourse comparison  
- Topic discovery in large text corpora  
- Text classification and sentiment analysis  



---

## Contributors
- Other Contributors: [Hareem Fatima](https://github.com/HareemFatima5) and [Fizza Kashif](https://github.com/fizza49)

---

##  License
This project is intended for **academic and research purposes only**.


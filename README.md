# Arabic Opinion Analysis & Detection 

This repository contains the code, datasets, and resources for a project developed as part of the **AI Project Creation Module** at the **Higher School of Technology of Meknès**.

The project focuses on **analyzing and detecting opinions expressed in Arabic text**, specifically from **web-scraped news articles**, and classifying them as **positive (With), negative (Against), or neutral** using Natural Language Processing (NLP) and Machine Learning techniques.

---

## 📌 Project Objectives

- Collect and preprocess Arabic text data from online news sources.  
- Perform **opinion annotation** (manual and aggregated).  
- Apply feature extraction techniques such as **TF-IDF**, **Bag of Words**, and **Word2Vec**.  
- Use **machine learning models** (SVM and others) for classification.  
- Explore performance benchmarking with **Lazy Predict**.  
- Visualize results using **word clouds** and metrics reports.  

---

## ⚙️ Tools & Techniques

- **Languages & Libraries**: Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn  
- **Web Scraping**: BeautifulSoup  
- **Feature Extraction**: TF-IDF, Bag of Words, Word2Vec  
- **Visualization**: WordCloud, Matplotlib  
- **Models**: Support Vector Machines (SVM), Lazy Predict benchmarking  
- **Data Handling**: Annotations, translation, and CSV-based datasets  

---

## 📂 Project Structure

```
Arabic-Opinion-Analysis&Detection/
│
├── Arabic-Opinion-Analysis&Detection.ipynb   # Main notebook with steps, code, and explanations
│
├── comments_output.txt                       # Cleaned scraped comments
├── annotations_1.txt                         # Annotator 1 labels
├── annotations_2.txt                         # Annotator 2 labels
├── annotations_3.txt                         # Annotator 3 labels
├── aggregated_annotations.txt                # Aggregated labels
│
├── Comments_annotated.csv                    # Final annotated dataset
├── translate_fr.csv                          # French translations
├── translate_en.csv                          # English translations
├── newdataset_2.csv                          # Dataset used for modeling
│
├── Amiri-Regular.ttf                         # Arabic font for word cloud rendering
```

---

## 🚀 Workflow

1. **Web Scraping**: Extract Arabic news comments and articles.  
2. **Preprocessing**: Cleaning, normalization, stopwords removal.  
3. **Annotation**: Manual labeling by multiple annotators, then aggregation.  
4. **Feature Engineering**: Representing text using TF-IDF, Bag of Words, and Word2Vec.  
5. **Model Training**: Training SVM and other classifiers.  
6. **Benchmarking**: Using Lazy Predict to compare model performances.  
7. **Visualization**: WordClouds and plots to interpret opinion distribution.  
8. **Evaluation**: Accuracy, F1-score, precision, recall.  

---

## 📊 Results

- Detected **positive, negative, and neutral opinions**.  
- SVM performed effectively with test scenarios.  
- WordCloud visualizations highlighted key opinion terms.  
- Lazy Predict provided quick benchmarking across multiple ML models.  

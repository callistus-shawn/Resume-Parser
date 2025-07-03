# Resume Classification and Job Recommendation System

The objective of this project is to develop an automated Resume Classification and Job Recommendation System. The system is designed to classify resumes into predefined professional categories such as Data Science, HR, or Software Engineering. Additionally, it recommends the most relevant job roles by computing the similarity between a candidate’s resume and available job descriptions. This project aims to streamline the candidate screening and job matching process using NLP and machine learning techniques.

* Extracted raw text content from resume PDFs using the `pdfplumber` library.
* Cleaned and preprocessed the resume dataset by removing duplicates, stopwords, hyperlinks, and unwanted symbols.
* Engineered domain-specific features from resumes such as skills, education, experience, and summaries to better capture professional context.
* Built and evaluated a multi-class classification model using a Random Forest classifier with a One-vs-Rest strategy on TF-IDF vectorized text data.
* Computed cosine similarity between processed resume text and job descriptions to recommend the top job matches for a given resume.
* Compared model performance using raw resume text versus extracted structured features to analyze the trade-offs in classification accuracy.

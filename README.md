IT Resume Dataset for NLP & Job Role Classification

🚀 Project Overview

While building a Resume Analyzer system, I realized that most publicly available resume datasets were either too small, poorly structured, or not suitable for real-world NLP modeling.

Instead of compromising, I decided to solve the problem myself.

This project contains a complete pipeline to:

Scrape resume data

Clean and preprocess text

Extract job titles using regex

Structure the dataset for NLP applications

The final dataset contains 9000+ resumes structured into machine learning–ready format.

📊 Dataset Information

The dataset contains the following columns:

• category

Represents the job domain under which the resume was categorized.

• job_title

Extracted job title from resume text using regular expressions.

• cleaned_text

Fully processed resume text after:

Removing emails and phone numbers

Removing headers and footers

Cleaning special characters

Normalizing whitespace

Removing duplicates

The dataset is ready for direct use in NLP and ML pipelines.

📎 Kaggle Dataset

The full dataset (106MB) is hosted on Kaggle:

👉 https://www.kaggle.com/datasets/haidermaseeh/resume-dataset

🛠 Tech Stack

Python

Requests

BeautifulSoup

Pandas

Regex

🧠 Key Learning Outcomes

Through this project, I gained hands-on experience in:

Web scraping large-scale text data

Text preprocessing for NLP

Regex-based pattern extraction

Dataset engineering

Structuring data for machine learning workflows

🎯 Potential Use Cases

Resume classification

Job role prediction

Resume similarity matching

Skill extraction

Recruitment analytics

Transformer-based NLP models (BERT, RoBERTa, etc.)

🔐 Privacy & Ethics

All personally identifiable information (emails, phone numbers) has been removed to ensure privacy protection.

This dataset was created for academic and research purposes.

⭐ If You Found This Useful

Feel free to star the repository and explore the Kaggle dataset.

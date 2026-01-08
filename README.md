# NLP-Based Marketing Insights from Customer Reviews

## Overview
This project applies Natural Language Processing (NLP) techniques to analyze customer reviews and extract insights relevant to marketing, SEO, and content strategy. The analysis focuses on understanding customer sentiment, identifying recurring themes, and linking textual insights to measurable business signals.

---

## Business Objective
Use customer review text to:
- Understand drivers of positive and negative customer sentiment
- Identify recurring topics and themes in customer feedback
- Surface insights that can inform marketing messaging, SEO keyword strategy, and content optimization

---

## Dataset
- Public Amazon product reviews dataset
- Fields used: ProductId, Score (rating), Summary, Text
- A representative sample of reviews was used to ensure efficient processing while maintaining realism

---

## Methodology

### Text Preprocessing
- Lowercasing and removal of non-alphabetic characters
- Stopword removal using NLTK
- Combination of review summary and body text for richer context

### Sentiment Analysis
- Applied VADER sentiment analysis to compute compound sentiment scores
- Validated sentiment results against customer ratings (Score)

### Validation
- Observed a moderate positive correlation (≈ 0.52) between sentiment scores and user ratings
- This confirms alignment between textual sentiment and explicit customer feedback

### Keyword Extraction (TF-IDF)
- Used TF-IDF to identify high-signal terms across customer reviews
- Applied frequency thresholds to reduce noise and improve interpretability

### Topic Modeling
- Applied Latent Dirichlet Allocation (LDA) to identify common themes in reviews
- Extracted five interpretable topics representing product experience, pricing, taste, and usage contexts

### Topic-Level Sentiment Analysis
- Assigned each review to its dominant topic
- Compared average sentiment scores across topics to identify relative strengths and pain points

---

## Key Findings

- Topics related to product taste, beverages, and flavor variety showed the highest average sentiment
- Topics associated with product expectations and usage context showed comparatively lower sentiment
- Pricing and ordering experience topics demonstrated generally positive sentiment, supporting conversion-focused messaging

---

## Marketing Insights
- Topics with lower average sentiment scores highlight potential customer pain points and areas for messaging or product improvement
- High-sentiment topics reveal language and features that resonate with customers and can be emphasized in SEO and content strategy
- NLP-driven insights can support keyword targeting, content optimization, and customer experience improvements

---

## Tools & Technologies
- Python  
- pandas, NumPy  
- scikit-learn  
- NLTK  
- matplotlib, seaborn  

---

## Business Impact
This analysis demonstrates how NLP can:
- Transform unstructured customer feedback into actionable marketing insights
- Support data-driven SEO and content decisions
- Improve alignment between customer voice and brand messaging

---

## Next Steps
- Expand analysis by product category or brand
- Incorporate review helpfulness signals for prioritization
- Apply similar methodology to social media or search query data

---

## Author
Mikayil Badalov
GitHub: https://github.com/Dasirak8

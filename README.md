# AI-Based-News-Classification-Using-NLP-and-Unsupervised-Learning
Project Overview

This project implements an AI-driven system to automatically categorize news articles into meaningful categories like Sports, Politics, Entertainment, Business, and Technology. The system uses NLP embeddings and unsupervised learning to reduce manual effort, improve accuracy, and enhance content personalization for media organizations.

Key Features
- Converts news articles into dense embeddings using Sentence Transformers (all-MiniLM-L6-v2).
- Measures semantic similarity between articles using cosine similarity.
- Groups articles into clusters with K-Means, optimized using the Elbow Method and Silhouette Score.
- Maps numeric clusters to real-world categories for easy interpretation.
- Evaluates clustering accuracy against human-labeled categories using precision, recall, F1-score, and accuracy metrics.
- Performs error analysis to understand misclassifications and borderline cases.

Technologies Used
- Python
- Pandas & NumPy – Data manipulation and analysis
- Matplotlib & Seaborn – Data visualization
- Sentence Transformers – NLP embeddings
- Scikit-learn – K-Means clustering and evaluation metrics
- Torch – GPU-based embedding computation

Methodology
1. Data Preprocessing: Clean and remove duplicates.
2. Embedding Generation: Convert text to dense vectors capturing semantic meaning.
3. Similarity Analysis: Measure semantic similarity between articles.
4. Clustering: Apply K-Means to group articles into clusters.
5. Cluster Mapping: Assign clusters to meaningful news categories.
6. Evaluation: Compare predicted categories with actual labels.
7. Error Analysis: Examine misclassified articles and distances to cluster centers.

Dataset
- Contains textual news articles.
- Separate file with human-labeled categories for validation.

Outcome
- Efficient automatic categorization of news articles.
- Reduces manual workload and improves content organization.
- Scalable solution for media organizations handling large volumes of text.

Future Scope
- Real-time updates for live news feeds.
- Finer categorization using hierarchical or density-based clustering.
- Integration with recommendation systems for personalized content delivery.

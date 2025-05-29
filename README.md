# Word2Vec Embedding Exploration

This project explores word embeddings using the pre-trained Google News Word2Vec model. It demonstrates how words can be represented in vector space and how semantic relationships can be analyzed through vector operations.

## 🚀 Features

- Loaded Google News pre-trained Word2Vec model (300-dimensional vectors)
- Performed word similarity and analogy tasks
- Visualized high-dimensional embeddings using PCA and t-SNE
- Compared with NLTK-based word embeddings and POS tagging

## 🛠️ Technologies Used

- Python
- Gensim
- Matplotlib / Seaborn
- Scikit-learn 

## 📂 Project Structure

- `word2vec_exploration.ipynb`: Main notebook with code and outputs
- `data/`: Preprocessed data 
- `plots/`: Embedding visualizations

## 📊 Sample Results

- Similar words to "king": `queen`, `monarch`, `ruler`
- Analogy example: `king - man + woman ≈ queen`

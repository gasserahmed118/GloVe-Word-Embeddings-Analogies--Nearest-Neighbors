🔍 Overview

This project demonstrates how pre-trained GloVe word embeddings can be used to capture semantic relationships between words. It explores word analogies, nearest neighbor search, and vector similarity using two different embedding sizes (50-dimensional and 300-dimensional). The project highlights how vector arithmetic can represent linguistic patterns such as gender, geography, and semantics.

⚙️ How It Works

The project loads pre-trained GloVe embeddings and stores them as numerical vectors. Each word is represented as a dense vector in a high-dimensional space. Semantic similarity is measured using cosine distance or Euclidean distance, and analogies are solved using vector arithmetic (w1 − w2 + w3). Nearest neighbors are found by computing pairwise distances between vectors and selecting the closest matches.

🧠 Pretrained Embeddings

The project uses GloVe (Global Vectors for Word Representation) embeddings trained on large text corpora. Two models are evaluated:
   1. GloVe 50D – smaller, faster, and lightweight
   2. GloVe 300D – larger, more expressive, and semantically richer
Comparing both models highlights how vector dimensionality affects analogy quality and semantic accuracy.

📌 Key Features

1. Word analogy solving (e.g., king − man + woman ≈ queen)
2. Nearest neighbor search in embedding space
3. Support for cosine and Euclidean distance metrics
4. Comparison between 50D and 300D GloVe embeddings
5. Efficient vectorized distance computation

📁 Project Structure
glove-word-embeddings/
│
├── notebook.ipynb
│   # Jupyter notebook containing all experiments,
│   # analogy solving, and nearest neighbor analysis
│
├── README.md
│   # Project overview and documentation
│
└── requirements.txt
    # Required Python libraries

🚀 Use Cases

1. Learning word embeddings and vector semantics
2. Exploring linguistic patterns in NLP
3. Comparing embedding dimensionality effects
4. Educational demonstrations of vector arithmetic
5. Prototyping similarity-based NLP applications

⚠️ Limitations

1. Static embeddings (no contextual meaning)
2. English-only vocabulary
3. Out-of-vocabulary words are not supported
4. Requires loading large embedding files into memory

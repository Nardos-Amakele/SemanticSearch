##Semantic Document Search with Sentence Transformers and FAISS
This project demonstrates how to perform semantic document search using Sentence Transformers for embedding generation and FAISS for efficient similarity-based retrieval. The code processes a dataset, generates embeddings, and enables querying for similar documents.
##How It Works
Data Loading:
Reads train.csv and valid.csv from Google Drive.
Text Cleaning:
Cleans text data by removing unwanted characters and formatting.
Embedding Generation:
Combines the title and body of documents and encodes them using Sentence Transformers.
Indexing:
Adds embeddings to a FAISS index for fast similarity search.
Querying:
Accepts a user query, computes its embedding, and finds the top 5 most similar documents.

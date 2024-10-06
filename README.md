# CISI-Search-Engine-Project


The project is committed to the use of information retrieval and natural language processing in the creation and operation of an efficient search engine for documents from the CISI dataset.



Overview
The CISI Search Engine combines several advanced techniques for processing and retrieving documents based on user queries. It incorporates:

Preprocessing: Text cleaning, stopword removal, and stemming.
Indexing: Efficient document indexing using the PyTerrier framework.
TF-IDF Retrieval: A classical retrieval model based on Term Frequency-Inverse Document Frequency for initial document ranking.
Query Expansion: RM3 algorithm for improving query relevance.
Ranking: BERT for re-ranking results based on semantic understanding.


Features
Document Retrieval: Retrieve relevant documents based on user queries using TF-IDF.
Query Expansion: Automatically expands queries to improve retrieval results.
BERT-based Reranking: Enhances the relevance of search results using deep learning.
Interactive Web Interface: Users can interact with the search engine via a simple web interface.


Acknowledgments
This project uses various libraries and tools including:

PyTerrier for information retrieval and TF-IDF implementation.
Transformers for leveraging pre-trained models like BERT.
NLTK for natural language processing tasks.

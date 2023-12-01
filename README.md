# Knowledge-Enhanced-Chatbot-for-Project-Management-Risk
# Overview
This project focuses on developing a Knowledge-Enhanced Chatbot to facilitate project management risk understanding. Leveraging Natural Language Processing (NLP) techniques and Graph Neural Networks (GNN), the chatbot extracts knowledge from a book on project management risk, creating an interactive and informative user experience.

# Features
**NLP Knowledge Extraction**:

Utilizes NLP methods, including keyword extraction, definition extraction, and Word2Vec embeddings.
Incorporates pretrained models like ReBEL for concept and relationship extraction.



**Graph Neural Network (GNN) Implementation**:



Implements a GNN model using techniques such as message passing, Graph Attention Network (GAT), and Graph Convolutional Network (GCN) for effective knowledge representation.




**User Interaction and Query Understanding**:

Integrates Rasa for query understanding, enabling users to interact effectively with the chatbot.
**Interactive Interface**:

Implements a Flask-based interface with both simple and advanced search methods for an engaging user experience.

Getting Started
Prerequisites
Python 3.x

# Usage




**1) Extract Knowledge from the Book**:

  * Provide the book's structure in the book.pdf file.
  * Execute python extract_process.py and extract_sub_title.py to extract titles, subtitles, and content.




**2)Organize Structure**:

  * Combine extracted titles and subtitles in the organise_structure.ipynb file.
  * Apply different regex and Word2Vec techniques for extracting keywords, synonyms, and definitions.
  * Save the processed data as a CSV file.




**3)Use ReBEL for New Concepts and Relationships**:

  * Execute python rebel.py to leverage ReBEL for extracting new concepts and relationships.
  * Apply search using SentenceTransformer and indexing to search for these new concepts and their content.
  * Save the new concepts combined with the old ones into a CSV file.




**4)Model Training and Link Prediction with GNN**:

  * Use the model.py file to read the CSV file with concepts and relationships.
  * Convert concepts with features into embedding vectors and relationships into edge embeddings.
  * Utilize GNN for link predictions.


    
**5)Chatbot Pipeline with Rasa and Flask:**




  * Use the chatpipeline.py file to read all concepts with relationships. 
  * Combine with Rasa for query understanding.
  * Implement a Flask-based web interface for presenting the chatbot.



## Acknowledgment and Disclaimer

This project involves the extraction of knowledge from a book on project management risk. It is essential to clarify that:

- The content extracted from the book is for educational purposes only.
- I do not claim ownership of the book's content, and all credits for the information go to the respective authors.
- This project is not intended for commercial use or profit.

Please ensure that you comply with copyright and intellectual property laws when using and sharing the extracted knowledge.

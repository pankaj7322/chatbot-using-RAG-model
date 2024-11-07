# Health FAQ Chatbot

This project implements a health FAQ chatbot using Qdrant for efficient storage and retrieval of answers to common health questions. It leverages the Sentence Transformers library to generate embeddings for semantic search, allowing users to get quick and accurate responses to their queries.

## Features

- Store and retrieve health-related questions and answers.
- Semantic search capabilities using embeddings from Sentence Transformers.
- Easy integration with the Qdrant vector database.

## Getting Started

### Prerequisites

- Python 3.x
- Access to Qdrant cloud service
- Required Python libraries (see Installation section)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/pankaj7322/chatbot-using-RAG-model.git
   cd chatbot-using-RAG-model
   ```
2. Install the required libraries:
    ```bash
    pip install sentence-transformers qdrant-client numpy cohere
    ```
3. To run the chatbot
    ```bash
    run the last cell of the ipynb file
    ```
4. Example of questions
    - What are the symptoms of diabetes.?
    - How often should I get a check-up.?
    - What should I do in case of an emergency.?
      
## Contributing
Contribution are welcome! Please fork the repository and submit a pull request for any improvement of fixes.

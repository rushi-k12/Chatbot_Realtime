# Advanced NLP Chatbot

This project showcases the development and deployment of a sophisticated chatbot that leverages advanced Natural Language Processing (NLP) techniques to provide intelligent responses to user queries.

## Features

1. **API Integration with Hugging Face**: Utilizes Hugging Face's extensive suite of NLP models and libraries, including transformers and embeddings, to enhance the chatbot's ability to understand and generate responses based on complex queries.

2. **Search and Retrieval**: Integrates APIs such as Groq for efficient search and retrieval of relevant information from a variety of sources, enhancing the chatbot's knowledge base dynamically.

3. **Question Answering**: Implements RetrievalQA from LangChain to process user questions, retrieve relevant documents, and generate precise answers using AI models like Mixtral-8x7b-32768.

4. **Text Processing**: Employs RecursiveCharacterTextSplitter from LangChain to preprocess and chunk text, optimizing the handling of large datasets and ensuring efficient query processing.

5. **Streamlit Application**: Develops a user-friendly interface using Streamlit, enabling seamless interaction with the chatbot. Users can input queries and receive AI-generated responses, enhancing accessibility and usability.

6. **Deployment on Hugging Face Spaces**: Ensures scalability, reliability, and easy access for users by deploying the application on Hugging Face Spaces. Leverages cloud-based infrastructure to handle varying loads and ensure consistent performance.

## Repository Contents

- `res/`: Directory containing resource files.
- `.gitignore`: Specifies files and directories to be ignored by Git.
- `LICENSE`: The license for this project.
- `README.md`: Project documentation.
- `app.py`: Main application script for running the Streamlit app.
- `config.py`: Configuration file containing various settings and parameters.
- `requirements.txt`: List of dependencies required to run the application.
- `res.zip`: Zipped resource files.
- `researcher.py`: Script containing the core logic for searching, retrieving, and processing information.

## Usage
Open your web browser and navigate to the URL provided by Streamlit (usually http://localhost:8501).
Enter your query in the input field and get AI-generated responses from the chatbot.

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

# Advancing Content-Based Recommendations: Integrating Large Language Models in Chatbots

## Overview

This project explores the integration of Large Language Models (LLMs), specifically the llama3 model powered by ollama, within a chatbot framework to improve content-based recommendations. The primary focus is on utilizing the llama3 model with Retrieve-and-Generate (RAG) capabilities to convert structured JSON data into meaningful embeddings. These embeddings are foundational for both answering user queries and generating personalized recommendations.

## Key Contributions

- **Embedding Generation**: Utilizing llama3's capabilities to transform JSON data into embeddings that capture semantic relationships and context.
- **Recommendation System**: Enhancing the chatbot’s ability to provide relevant and personalized recommendations based on user interactions and preferences.
- **User Engagement**: Improving the overall user experience by delivering more accurate and context-aware responses.

## Methodology

### 1. Dataset Preparation
- **CSV to JSON Conversion**: Python scripts convert the initial dataset from CSV format to JSON format to ensure compatibility with the llama3 model.

### 2. Data Upload and Preprocessing
- **File Upload and Text Extraction**: The `upload.py` script handles the upload of PDF, TXT, and JSON files, converting PDF content to text, cleaning and normalizing the text, and splitting it into manageable chunks.

### 3. Embedding Generation
- **Utilizing Llama3**: The `localrag.py` script employs the llama3 model to generate embeddings from the uploaded content, capturing semantic relationships and contextual information.

### 4. Recommendation System Enhancement
- **Context-Aware Recommendations**: The `localrag.py` script retrieves relevant context from the vault based on user input, refining queries and enhancing the relevance of the chatbot’s responses.

### 5. Evaluation and Validation
- **Empirical Evaluation**: Effectiveness of the integrated llama3 model is evaluated through empirical testing, measuring metrics such as user satisfaction.
- **User Studies**: User studies are conducted to gather qualitative feedback on the chatbot’s performance, providing insights into the accuracy and relevance of the recommendations.

## Dataset

### TMDB 5000 Movie Dataset
This dataset provides extensive metadata on approximately 5000 movies sourced from The Movie Database (TMDb), including plot summaries, cast and crew details, budget, revenue, genres, production companies, release dates, and more. It serves as a valuable resource for analyzing various aspects of movie success and characteristics.

## Conclusion

The integration of LLMs, specifically the llama3 model, within chatbot frameworks significantly enhances content-based recommendation systems. By leveraging llama3's capabilities, structured JSON data is successfully converted into meaningful embeddings, improving the chatbot's ability to provide relevant and context-aware responses. This integration results in higher user engagement and satisfaction, setting a new benchmark for conversational AI and recommendation systems.

## Future Directions

Future research may focus on optimizing retrieval and generation processes to further refine recommendation accuracy and responsiveness. Exploring the integration of other advanced LLMs and machine learning techniques could pave the way for even more sophisticated and user-centric applications in recommendation technology.

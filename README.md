# AI-Powered-PDF-Document-Summarizer-and-Analyzer

AI-Powered PDF Document Summarizer and Analyzer is a Python tool designed for automatic extraction and analysis of content from PDF documents. It leverages advanced AI models for summarization, insight extraction, and sentiment analysis.

Features
PDF Text Extraction: Uses PyPDF2 to extract text from PDF files.
Summarization: Utilizes the BART model for generating concise document summaries.
Key Insights Extraction: Uses spaCy for NLP-based rule extraction to gather meaningful insights.
Sentiment Analysis: Analyzes the sentiment of the document using a sentiment analysis model from Hugging Face.
JSON Output: The analysis results (summary, key insights, sentiment) are saved in a structured JSON format.

Technologies
Python Libraries: PyPDF2, transformers, nltk, spaCy
Models: facebook/bart-large-cnn for summarization, Hugging Face sentiment analysis pipeline for sentiment detection, and spaCy for NLP tasks.

How to Use:
Install dependencies:

pip install PyPDF2 transformers nltk spacy

Download necessary NLTK data:

nltk.download('punkt')


Run the script:
Upload your PDF file when prompted.
The program will process the document and provide a summary, key insights, and sentiment analysis.


Output:
View the analysis in the console.
The analysis results will be saved to analysis_results.json.

License
This project is open-source and available under the MIT License.


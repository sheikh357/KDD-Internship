# KDD-Internship

# PubMed Article Summarizer
## Overview
This project aims to create a web application that summarizes PubMed articles. It involves data exploration and preparation, web application development, and optional integration of Generative AI models for text summarization. The project is part of the KDD Summer Internship Assignment 2024.
### Table of Contents

# Data Exploration and Preparation
### Quality of Data Cleaning
The PubMed Summarization dataset was loaded from Hugging Face, and the first 100 samples were selected for both the document and section levels. Data cleaning involved removing extra spaces and special characters, and converting the text to lowercase.

### Thoroughness of Preprocessing
Preprocessing steps included:

Removing extra spaces
Removing special characters
Converting text to lowercase

Preprocessing was applied consistently across the dataset to ensure uniformity and readiness for summarization.

# Web Application Development
### Functionality of the Application
The web application was developed using Streamlit. It allows users to input or upload PubMed articles and generates summaries using both extractive and generative methods.

### Usability of the Interface
The interface is simple and user-friendly, enabling users to easily upload articles and view the original text alongside the generated summaries.

### Design and Aesthetics
The design is minimalistic and functional, focusing on ease of use.

# Generative AI Model Integration
### Selection of the Model
OpenAI's GPT-4 was selected for generative summarization due to its state-of-the-art performance in natural language understanding and generation.

### Fine-tuning of the Model
Fine-tuning was not performed due to resource constraints. Instead, the model was used directly via the OpenAI API.

### Performance Evaluation
The performance of the generative summaries was evaluated subjectively by comparing them with extractive summaries and the original abstracts.

### Advanced Features
No advanced features such as user authentication, summary length/style options, interactive visualization, video generation, or image generation were implemented due to time constraints.


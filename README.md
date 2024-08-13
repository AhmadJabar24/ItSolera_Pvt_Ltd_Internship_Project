# Text Generation with GPT-2

This project is a Streamlit-based web application that uses the GPT-2 model for text generation. It allows users to upload a CSV file, preprocess text, and generate stories or dialogues based on user-provided prompts. 

## Project Overview

- **Functionality:**
  - Upload a CSV file containing text data.
  - Preprocess the text by converting it to lowercase, removing punctuation, and tokenizing it into sentences.
  - Generate stories or dialogues using the GPT-2 model based on user prompts.
  - Display generated text on the web interface.

- **Technologies Used:**
  - **Streamlit:** For creating the interactive web interface.
  - **Pandas:** For handling and processing the CSV data.
  - **Transformers (Hugging Face):** For loading and using the GPT-2 model.
  - **NLTK:** For text preprocessing, including sentence tokenization.

## Features

- Upload and view a CSV file.
- Generate text based on prompts for both stories and dialogues.
- Customize text generation with parameters like `max_length`, `temperature`, `top_k`, and `top_p`.

## Installation and Setup

Follow these steps to set up the project on your local machine:

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/your-repo.git
cd your-repo

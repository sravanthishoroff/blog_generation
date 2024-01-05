# blog_generation

# Blog Generator using Streamlit 🤖

## Overview

This project utilizes Streamlit to create a simple web interface for generating blogs using the LLAMA 2 language model. Users can input a blog topic, specify the number of words, and select a writing style for the generated blog.

## Prerequisites

- Python 3.x
- Ensure required Python packages are installed:
  ```bash
  pip install streamlit langchain

##  Usage

1. Clone Repository
    git clone https://github.com/your-username/blog-generator.git
2. Navigate to the Project Directory
    cd blog-generator
3. Install dependencies:
    pip install -r requirements.txt
4. Run the streamlit app
    streamlit run app.py
5. Open the provided URL in your web browser.

6. Enter the blog topic, specify the number of words, and choose a writing style.

7. Click the "Generate" button to get a generated blog.

## Project Structure
app.py: Main Streamlit application script.
models/llama-2-7b-chat.ggmlv3.q8_0.bin: LLAMA 2 language model file.
langchain/prompts.py: PromptTemplate class for generating prompts.
langchain/llms.py: CTransformers class for loading LLAMA models.

## Acknowledgments
This project uses the Streamlit library for creating interactive web applications.
LLAMA 2 is a language model used for generating responses.

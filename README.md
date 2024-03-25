# Diabetes Chatbot 🤖🩺

This repository contains a chatbot designed to provide assistance and information related to diabetes management. The chatbot is built using the Hugging Face Llama2 model and trained using data from the AMERICAN_DIABETES_ASSOCIATION.pdf document. Additionally, efforts are underway to integrate Gemini or Gemma to further enhance its capabilities.

## Requirements

To run the chatbot, ensure you have the following dependencies installed:

- pinecone-client
- ctransformers
- sentence-transformers
- python-dotenv
- pypdf
- langchain

## Usage

1. Clone the repository:

   ```bash
   https://github.com/karan-panda/diabetes-chatbot
   ```

2. Install the Requirements:

    ```bash
    pip install -r requirements.txt
    ```

3. Create a .env file in the root directory and add your Pinecone credentials

    ```
    # .env file

    PINECONE_API_KEY = "xxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
    PINECONE_API_ENV = "xxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
    ```
4. Download the quantize model from the provided link and place it in the model directory

    You can download the model from the Hugging Face model hub [Click here](https://huggingface.co/TheBloke/Llama-2-7B-Chat-GGML/tree/main).
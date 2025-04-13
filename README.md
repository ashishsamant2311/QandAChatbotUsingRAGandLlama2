# Llama 2 - Offline Model Download and RAG-based QA Application

This repository contains two Jupyter notebooks designed to work with the Llama 2 13B model:

1. **LLama2_13B_Quantized_Offline_Download**: This script facilitates downloading and setting up a quantized version of the Llama 2 13B /Mistral-7B-Instruct-v0.2 model for offline use.
2. **Llama2_13b_4bit_RAG_QA_EmployeeHandbook_Final**: This script demonstrates a Retrieval-Augmented Generation (RAG) pipeline to answer questions based on the content of a PDF.

## Features

### Notebook 1: LLama2_13B_Quantized_Offline_Download
- Downloads a quantized version of the Llama 2 13B model.
- Ensures compatibility with offline environments.
- Provides step-by-step guidance to set up the model on your local system.
- Focuses on resource-efficient deployment using 4-bit quantization.

### Notebook 2: Llama2_13b_4bit_RAG_QA_EmployeeHandbook_Final
- Implements a RAG pipeline for question-answering tasks.
- Extracts content from a PDF document for knowledge retrieval.
- Uses Llama 2 13B as the base model for generating answers.
- Includes pre-processing steps for document ingestion and embedding creation.
- Features seamless integration of question answering based on indexed document data.

## Requirements

### General
- Python 3.8 or above
- Jupyter Notebook or JupyterLab

### Dependencies
Install the required packages using the following command:
```bash
pip install -r requirements.txt
```

### Hardware
- A system with at least 16GB of RAM (recommended).
- For GPU acceleration, ensure compatibility with CUDA and install the appropriate drivers.

## Usage

### Step 1: Download the Model
1. Open the `LLama2_13B_Quantized_Offline_Download.ipynb` notebook.
2. Follow the steps to download and set up the model.
3. Ensure the downloaded model is saved in a directory accessible for the RAG pipeline.

### Step 2: Set Up the RAG Application
1. Open the `Llama2_13b_4bit_RAG_QA_EmployeeHandbook_Final.ipynb` notebook.
2. Place the PDF document to be used for Q&A in the specified directory.
3. Run the cells to:
   - Preprocess the PDF.
   - Generate embeddings for document content.
   - Initialize the RAG pipeline with the downloaded model.
4. Input your questions and retrieve answers based on the PDF content.

## Highlights
- **Offline Accessibility**: The quantized model setup ensures full functionality without internet access.
- **Efficient Resource Usage**: 4-bit quantization allows for significant memory savings, enabling deployment on less powerful hardware.
- **RAG Pipeline**: Combines the strengths of information retrieval and generative AI for accurate and context-aware responses.

## File Structure
```
├── LLama2_13B_Quantized_Offline_Download.ipynb   # Offline model download setup
├── Llama2_13b_4bit_RAG_QA_EmployeeHandbook_Final.ipynb   # RAG QA application
├── requirements.txt                             # Python dependencies
└── README.md                                    # Project documentation
```

## Acknowledgments
- **Meta AI**: For developing the Llama 2 model.
- **Hugging Face**: For tools and libraries enabling seamless integration of advanced NLP models.

# Knowledge Point and Q&A Generator

This repository contains two Jupyter notebooks that extract and process text from a PDF to generate knowledge points and create question-answer pairs using OpenAI's GPT-4 model.

## Files

- **KP-Generator.ipynb**: Extracts and processes knowledge points from a PDF.
- **QA-GPT4.ipynb**: Generates question-answer pairs from the knowledge points using GPT-4.

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/yourusername/knowledge-qa-generator.git
    cd knowledge-qa-generator
    ```

2. Install the required Python packages:

    ```bash
    pip install PyPDF2 pandas openai
    ```

## Usage

1. **KP-Generator.ipynb**:
    - Extracts text from a specified PDF.
    - Processes and refines the text into knowledge points.
    - Saves the knowledge points to `knowledge_points.csv`.

2. **QA-GPT4.ipynb**:
    - Reads knowledge points from `knowledge_points.csv`.
    - Generates question-answer pairs using GPT-4.
    - Saves the Q-A pairs to `generated_qa_pairs.csv`.

## Notes

- Ensure you have an OpenAI API key to use the GPT-4 model.
- Adjust file paths and parameters as needed for your specific PDF.

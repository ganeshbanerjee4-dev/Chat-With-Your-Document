# Chat With Your Document 📄💬

This project is an interactive chatbot application that allows users to upload documents and ask questions directly from the content. The chatbot processes the document, understands its context, and generates relevant answers.
##  Features
- Upload and process documents (PDF, TXT, etc.)
- Ask natural language questions
- Get accurate, context-based answers
- Built using **Python + Jupyter Notebook**

##  Project Structure
- `Chat_With_Your_Doc_new.ipynb` → Main notebook with the chatbot logic

##  Requirements
Make sure you have installed:
- Python 3.9+
- Jupyter Notebook
- Required libraries (see imports in notebook)

You can install dependencies with:
```bash
pip install -r requirements.txt

## Usage Instructions

1. **Clone this repository.**
2. **Set your OpenAI API key as an environment variable:**

   - For Linux/macOS:
     ```
     export OPENAI_API_KEY="your_openai_api_key_here"
     ```
   - For Windows (PowerShell):
     ```
     setx OPENAI_API_KEY "your_openai_api_key_here"
     ```

3. **Run the notebook** `Chat_With_Your_Doc_new.ipynb` in Jupyter.
4. Upload your document (PDF, TXT, CSV) when prompted.
5. Start asking questions about your document in the chat interface.

## Important
- **Never commit or share your actual OpenAI API key publicly.**
- You must have a valid OpenAI API key to use the chatbot.
- For best results, upload documents with clear, extractable text.

## License
(Add license details here if needed)


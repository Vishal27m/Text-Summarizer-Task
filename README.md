📝 BART-based Text Summarizer
This is a simple AI utility that takes a long piece of text as input and returns a 3-line summary using the facebook/bart-large-cnn model from Hugging Face Transformers.

📌 Project Overview
Built as part of the AI & ML Internship at Senthuron, this summarizer tool demonstrates how state-of-the-art transformer models can be used to enhance internal workflows and educational platforms by condensing large blocks of text into concise summaries.

🚀 How It Works
User inputs a block of text.

Text is tokenized using BartTokenizer.

Tokens are passed to the BartForConditionalGeneration model.

The model returns a 3-line summary.

🧠 Model & Tools Used
Model: facebook/bart-large-cnn

Library: Hugging Face Transformers

Framework: PyTorch

Optional UI: Streamlit

🧪 Example
Input:
"Natural Language Processing (NLP) is a field of Artificial Intelligence that enables computers to understand, interpret, and generate human language..."

Output:

NLP enables machines to understand and interact using human language.

It powers tools like chatbots, translators, and summarizers.

This utility summarizes long texts into concise, readable insights.

📁 File Structure
bash
Copy
Edit
BART.py                      # Main summarizer script
BART_Text_Summarizer.ipynb  # Jupyter version (optional)
README.md                   # Project documentation
💻 Setup Instructions
Install dependencies:

bash
Copy
Edit
pip install transformers torch streamlit
Run the script (CLI/Notebook):

For Python script:

bash
Copy
Edit
python BART.py
For Streamlit UI (optional):

bash
Copy
Edit
streamlit run BART.py

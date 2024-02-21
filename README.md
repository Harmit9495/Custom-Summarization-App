# Custom-Summarization-App
Building Summarization Application with LangChain,  OpenAI and streamlit for front end

This code defines a Streamlit web application for custom summarization. Here's a breakdown of its functionality:

# User Interface Setup:
The application provides a sidebar with options to select the type of summarization chain (chain_type), adjust chunk size and overlap for text chunking, and configure the ChatGPT model parameters (temperature).
Users can also input a custom prompt and the path to a PDF file.

# Text Chunk Visualization:
If the "Debug chunk size" checkbox is selected, it displays an interactive text chunk visualization based on the input text, chunk size, and overlap.
Summarization:

# Users input a custom prompt and a PDF file path.
Upon clicking the "Summarize" button, the PDF file is loaded and split into chunks of text based on the specified chunk size and overlap.
The loaded text chunks are then passed through a summarization chain based on the selected chain_type.
The summarization chain generates summaries based on the provided input documents and the user prompt.
The resulting summaries are displayed in the Streamlit application interface.

# Language Model Selection:
Users can choose between two language models for summarization: ChatGPT and GPT-4. They can also adjust the temperature parameter for the ChatGPT model.
Overall, this application allows users to input a PDF file, specify summarization parameters, and generate custom summaries based on the provided input documents and prompts, utilizing either ChatGPT or GPT-4 language models. Additionally, it provides an option for interactive visualization of text chunks for debugging purposes.

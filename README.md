# Custom-Summarization-App
Building Summarization Application with LangChain,  OpenAI and streamlit for front end

This code defines a Streamlit web application for custom summarization. Here's a breakdown of its functionality:

# User Interface Setup:
The application provides a sidebar with options to select the type of summarization chain (chain_type), adjust chunk size and overlap for text chunking, and configure the ChatGPT model parameters (temperature).
Users can also input a custom prompt and the path to a PDF file.![ezgif-7-4ceb66f518](https://github.com/Harmit9495/Custom-Summarization-App/assets/52893215/b3f86081-775a-401d-9e07-0343f54398aa)


# Text Chunk Visualization:
If the "Debug chunk size" checkbox is selected, it displays an interactive text chunk visualization based on the input text, chunk size, and overlap.
Summarization:![2023-06-12-12-07-40](https://github.com/Harmit9495/Custom-Summarization-App/assets/52893215/bec53bdb-0c1d-4272-af31-9aab23bac540)


# Users input a custom prompt and a PDF file path.
Upon clicking the "Summarize" button, the PDF file is loaded and split into chunks of text based on the specified chunk size and overlap.
The loaded text chunks are then passed through a summarization chain based on the selected chain_type.
The summarization chain generates summaries based on the provided input documents and the user prompt.
The resulting summaries are displayed in the Streamlit application interface.
![ezgif-7-cbe45b9b7f](https://github.com/Harmit9495/Custom-Summarization-App/assets/52893215/8ff16644-a067-4117-baca-32a4ffedd336)

# Language Model Selection:
Users can choose between two language models for summarization: ChatGPT and GPT-4. They can also adjust the temperature parameter for the ChatGPT model.
Overall, this application allows users to input a PDF file, specify summarization parameters, and generate custom summaries based on the provided input documents and prompts, utilizing either ChatGPT or GPT-4 language models. Additionally, it provides an option for interactive visualization of text chunks for debugging purposes.
![ezgif-7-d9f2333a8b](https://github.com/Harmit9495/Custom-Summarization-App/assets/52893215/d65478c4-7b52-45b1-ad11-dc101e3af0ae)

<h1 align="center">
FileGPT 🤖
</h1>

Read the article to know how it works: <a href="https://medium.com/@dan.avila7/file-gpt-conversaci%C3%B3n-por-chat-con-un-archivo-698d17570358">Medium Article</a>

With File GPT you will be able to extract all the information from a file.
You will obtain the transcription, the embedding of each segment and also ask questions to the file through a chat.

All code was written with the help of <a href="https://codegpt.co">Code GPT</a>

<a href="https://codegpt.co" target="_blank"><img width="753" alt="Captura de Pantalla 2023-02-08 a la(s) 9 16 43 p  m" src="https://user-images.githubusercontent.com/6216945/217699939-eca3ae47-c488-44da-9cf6-c7caef69e1a7.png"></a>

<hr>
<br>

# Features

- Read any pdf, docx, txt or csv file
- Embedding texts segments with Langchain and OpenAI (**text-embedding-ada-002**)
- Chat with the file using **streamlit-chat** and LangChain QA with source and (**text-davinci-003**)

# Running Locally

1. Clone the repository

```bash
git clone https://github.com/davila7/file-gpt
cd file-gpt
```
2. Install dependencies

These dependencies are required to install with the requirements.txt file:

* openai
* pypdf
* scikit-learn
* numpy
* tiktoken
* docx2txt
* langchain
* pydantic
* typing
* faiss-cpu
* streamlit_chat

```bash
pip install -r requirements.txt
```
3. Run the Streamlit server

```bash
streamlit run app.py
```

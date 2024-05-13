# RAG chatbox from website 

## Setup 
Create a virtual environemnt: 
```sh
python3 -m venv .venv
```

Activate it and install dependencies: 
```
pip install -r requirements.txt
```

To activate the environment on Windows: 
```python
.venv\Scripts\Activate.ps1
```

Get an OpenAI API key from https://platform.openai.com/ and store it at `.streamlit/secrets.toml` as: 
```sh
openai_key = "<API_KEY>"
```


## Running the app
```
streamlit run .\streamlit_app.py
```

## Directory Structure 
- `scraper/` have scripts to crawl html pages.  
- `data/` stores data that the llama index RAG pulls on.  


## Demo 

![alt text](https://github.com/Hazarre/rag-chatbot/blob/main/rag-demo.png?raw=true)


## References: 
https://blog.streamlit.io/build-a-chatbot-with-custom-data-sources-powered-by-llamaindex/






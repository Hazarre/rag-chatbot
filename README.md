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

## Running the app
```
streamlit run .\streamlit_app.py
```

## Directory Scructure 
- `scraper/` have scripts to crawl html pages.  
- `data/` stores data that the llama index RAG pulls on.  


## References: 
https://blog.streamlit.io/build-a-chatbot-with-custom-data-sources-powered-by-llamaindex/



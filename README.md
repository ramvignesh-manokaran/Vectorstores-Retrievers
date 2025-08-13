# Vector stores and Retrievers

LangChain's vector store and retriever abstractions. These abstractions are designed to support retrieval of data-- from (vector) databases and other sources-- for integration with LLM workflows. They are important for applications that fetch data to be reasoned over as part of model inference, as in the case of retrieval-augmented generation.

We will cover 
- Documents
- Vector stores
- Retrievers

## Setting Up environment

1.Run below command to create python environment
 ```bash
conda create -p venv python==3.10 -y  
```

2. Create requirements.txt file with required libraries.

3. Activate environment by running below command.
 ```bash
conda activate venv/ 
```
4. Install all libs in requirements.txt using below command.
 ```bash
pip install -r requirements.txt
```
5. Create an .env file with below keys before executing ipynb files. HF_TOKEN="" LANGCHAIN_API_KEY="" LANGCHAIN_PROJECT="" GROQ_API_KEY=""

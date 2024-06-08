# Langchain RAG Tutorial

Install dependencies.

```python
pip install -r requirements.txt
```

Create the Chroma DB.

```python
python create_database.py
```

Query the Chroma DB.

```python
python query_data.py "what is the soaking time during shut in"
```

You'll also need to set up an OpenAI account (and set the OpenAI key in your environment variable) for this to work.

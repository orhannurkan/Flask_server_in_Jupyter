# Flask API in Jupyter Notebook runs as a Service

- Download this two files (client.ipynb and server.ipynb)

- install Flask : pip install Flask

- First open server.ipynb file and run all

- Then open client.ipynb file and run all

- To see different answers from the server file run these lines

```python
response = requests.get('http://127.0.0.1:5000/predict',timeout=3)
response.text
```

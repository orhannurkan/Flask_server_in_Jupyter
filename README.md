# Flask API in Jupyter Notebook runs as a Service

- Download this two files (client.ipynb and server.ipynb)

- In the terminal run this codes : 
```terminal
pip install Flask
pip install requests
pip install random
```

- First open server.ipynb file and run all

- Then open client.ipynb file and run all

- To see different answers from the server file run these lines

```python
response = requests.get('http://127.0.0.1:5000/predict')
response.text
```

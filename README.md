# Flask API in Jupyter Notebook runs as a Service

- Download this two files (client.ipynb and server.ipynb)

- Run these codes in the terminal:
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



If you want to run Jupyter notebook file in terminal, you can.

(just you should install ipython library : pip install ipython)

- in terminal run this code : ipython
- then to run your Jupyter notebook file use this code : %run server.ipynb
- it runs like a python file(.py) and waits for requests.

# Langflow-With-Ollama
How to set up and run Langflow with Ollama in a ENV on windows.

## Reqiremnets


to use langflow its best to set it up in a python env (enviorment)  runing python versions >=3.9 and <3.12.

1. Create a new Conda environment with Python 3.9:
```
conda create -n langflow-py39 python=3.9
```

2. Activate the new environment:
```
conda activate langflow-py39
```

3. Try installing langflow:
```
pip install langflow
```
   or for local
```
pip install langflow[local]
```

4. Download & install the Ollama windows installer from [Ollama](https://github.com/ollama/ollama)

5. Open Ollama windows application

6. open url in browser you should see ``` Ollama is running ```
```
http://localhost:11434
```

7. Run langflow
```
langflow Run
```
You shoud see somethin like ( XXX is used as an exaple but yours will have numbers ) blick on te urn to run in the browser ``` ctrl + mouse click ```
```
 Welcome to ⛓ Langflow                             
                                                   
 Access http://xxx.0.0.1:xxxx                      
 Collaborate, and contribute at our GitHub Repo 🚀
```

8. Have fun 🎈🎉😁

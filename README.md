# rag_langchain

## Using the virtual environment

Create a virtual environment named `.venv` in the project root:

```
python3 -m venv .venv
```

Activate the virtual environment:

On Linux/macOS:

```
source .venv/bin/activate
```

On Windows (PowerShell):

```
.venv\Scripts\Activate.ps1
```

Install dependencies (if you have a requirements file):

```
pip install -r requirements.txt
```

Deactivate:

```
deactivate
```

Notes
 
- This repository uses a local virtual environment named `.venv` by convention. The environment was created with the system Python available as `python3`.
- If you need to install dependencies, create a `requirements.txt` or `pyproject.toml` and run `pip install -r requirements.txt` or use your preferred tool.

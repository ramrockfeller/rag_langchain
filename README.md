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

Try it

Run the included `hello.py` script with the virtual environment's Python to verify the venv is used:

```bash
.venv/bin/python hello.py
```

uv CLI

The project can be initialized and dependencies installed using the `uv` CLI if you have it installed.

- Initialize the project:

```bash
uv init
```

- Install dependencies using `uv` (if supported by your `uv` version):

```bash
uv install
uv add -r requirements.txt
```

- To install a single package:

```bash
uv add <package-name>
uv add ipykernel # this is for jupiter notebook
```

Alternate (using pip)

If you prefer to use pip directly (or `uv` is not available), install dependencies from `requirements.txt`:

```bash
# install all dependencies listed in requirements.txt
pip install -r requirements.txt

# or install a single package
pip install <package-name>
```

If you previously used commands like `uv add -r requirements.txt` to add packages, the equivalent pip command is shown above (`pip install -r requirements.txt`).

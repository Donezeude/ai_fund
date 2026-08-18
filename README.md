uv venv
Using CPython 3.14.5 interpreter at: /usr/bin/python
Creating virtual environment at: .venv
Activate with: source .venv/bin/activate


COMMANDS

uv venv -> creates the uv virtual environment in your folder with the latest python version

uv venv --python {{version number}} -> specifies the python version you want

source .venv/bin/activate -> this activates the virtual environment

uv init -> generates pyproject.toml which is a text based file that makes your project environment reproducible.

uv add {{libraries}} -> puts your libraries in the pyproject.toml

uv pip freeze > requirements.txt -> this generates a list of installed dependencies



LIBRARIES

requests -> used to send HTTP requests to websites, web servers, and APIs

torch    -> it's a machine learning and deep learning framework used to build, train, and deploy artificial neural networks

jupyter  -> used to create and run interactive computational documents known as Jupyter Notebooks


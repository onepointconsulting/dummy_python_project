# Dummy Template Project

## Installation Instructions

This project can be installed with Conda.

Here are the commands to create the environment:

```
conda create -n dummy_project python=3.11
conda activate dummy_project
pip install poetry
poetry install
```

# Configuration

This project uses .env for configuration. These are the parameters:

```
OPENAI_API_KEY=<your key>
OPENAI_MODEL=<a model like gpt-3.5-turbo-0613>
```


## Remarks
This project was created using:

```
poetry init
```

## Checking

If the project was correctly installed this should work:

```
python.exe .\dummy_project\config.py
```

# FEWSNET API Notebooks Repository

Welcome to the FEWSNET API Notebooks Repository!

This repository is a curated collection of Jupyter notebooks
designed to serve as a practical resource for understanding
and executing API calls. Our notebooks provide hands-on
examples, required libraries and tutorials that guide you through
various data queries and manipulations using APIs.

## Features

`Comprehensive Guides:` Step-by-step notebooks on how to
interact with different public APIs, complete with detailed explanations.

`Ready-to-Use Code:` Snippets that are fully executable and can
be easily adapted for various data analysis tasks.

`Resource-Rich Documentation:` Markdown cells within notebooks
offer rich documentation and context for each step of the API interaction process.

`Community-Driven:` Opportunities for the community to contribute and
enhance the repository with new examples and improved methods.

## Getting Started

To get started:

1. Clone the repository/download the notebook to your local machine.
2. Create a virtual environment and Install the necessary dependencies
listed in the requirements.txt file. (Each project folder has a requirements.txt
file that lists the libraries used).
3. Open the directory on Jupyter/Jupyterlab
4. Explore the notebooks directory to find examples relevant to
your needs and Follow the instructions within each notebook to run the code cells.

## Python Set-up guide

### 1. Clone the entire repository using HTTP

- Navigate to the main page of the repository. In this case
[here](https://github.com/FEWS-NET/data-notebook-hub)
- click on the `Code` button and copy the url under HTTPS.
- Open a terminal window and navigate to your desired directory.
- On the terminal use the following commands:

```text
git clone <your url here> {desired_local_repo_name}
```

This will clone the repository to your local machine.

PS. {desired_local_repo_name}
is optional you can use a desired name or leave it.

### 2. Creating a virtual environment and installing requirements

When creating a virtual environment, navigate to the directory where the virtual environment
will be created and on the terminal, enter the following commands:

```text
python -m venv env_name
```

replace env_name with a preferred name for your virtual environment.

Next activate the virtual environment:

```text
source 'path-to-env'/bin/activate
```

Once the virtual environment is activated, install the requirements:

```text
pip install -r 'path-to-project-root-directory' requirements.txt
```

### 3. Open the Notebook/Notebooks directory on Jupyter (Jupyterlab)

On the terminal, with the  virtual environment activated. Run:

```text
jupyterlab 
```

This will instantiate a local server at port 8888 and open a tab on 
your browser where you can explore the notebooks and run them.
Alternatively, you can open them on Jupyter rathr than jupyter lab. to do this, run:

```text
jupyter notebook
```

This will also open a local server at localhost:8888 and open a new tab on your browser.

if the tab does not open automatically, check the output on the terminal and
copy the provided url and open it on your browser.

## General Libraries

- [Pymarkdownlnt](https://pypi.org/project/pymarkdownlnt/) - Linting library for
`.md` files
- Pandas
- Numpy
- requests
- Jupyter
- [nbdev2](https://www.fast.ai/posts/2022-08-25-jupyter-git.html) - Suitable for managing notebooks with multiple contributors

## Contributions

We welcome contributions from the community! If you have suggestions or
improvements, please see our `CONTRIBUTING.md` for guidelines on
how to make a pull request.

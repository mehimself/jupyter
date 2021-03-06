---
layout: episode
title: Sharing notebooks
teaching: 10
exercises: 0
questions:
 - How can I share notebooks with colleagues and the community?
objectives:
 - See what platforms and services exist to share Jupyter notebooks
 - Have a final discussion on notebooks in research.
---

## Sharing notebooks

- You can enter a URL, GitHub repo or username, or GIST ID in [`nbviewer`](https://nbviewer.jupyter.org/) and view a rendered Jupyter notebook
- Read the Docs can render Jupyter Notebooks via the [nbsphinx package](https://nbsphinx.readthedocs.io/)
- [Binder](https://mybinder.org/) creates live notebooks based on a GitHub repository
- [CoCalc](https://cocalc.com/) (formerly SageMathCloud) allows collaborative editing of notebooks in the cloud 
- Google's [colaboratory](https://colab.research.google.com/) lets you work on notebooks in the cloud, and you can [read and write to notebook files on Drive](https://colab.research.google.com/notebooks/io.ipynb)
- [Microsoft Azure Notebooks](https://notebooks.azure.com/) also offers free notebooks in the cloud
- [JupyterLab](https://github.com/jupyterlab/jupyterlab) supports sharing and collaborative editing of notebooks via Google Drive 
- [Notedown](https://github.com/aaren/notedown), [Jupinx](https://github.com/QuantEcon/sphinxcontrib-jupyter) and [DocOnce](https://github.com/hplgit/doconce) can take Markdown or Sphinx files and generate Jupyter Notebooks
- The `jupyter nbconvert` tool can convert a (`.ipynb`) notebook file to:
    - python code (`.py` file) 
    - an HTML file
    - a LaTeX file
    - a PDF file
    - a slide-show in the browser

Note: the Google, Microsoft and CoCalc platforms are free but have paid subscriptions for faster access to cloud resources


## Final discussion

- If you are already using Jupyter, what tasks do you use it for? 
- If you are new to Jupyter, do you see any possible use cases?
- Do you think Jupyter Notebooks can help tackle the problem of irreproducible results?

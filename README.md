# Learn Ngspice
Learning Ngspice is a difficult endeavor, with bewildering commands and syntax. You can explore the full power of Ngspice with the help of Python. We have created full-functioning notebooks that can be used with Google Colabs or Jupyter.
## Ngspice
[Ngspice](https://ngspice.sourceforge.io/) is an open-source circuit simulator for exploring and validating electronic designs. Experiment with design alternatives, optimize operation, and understand how operation changes under real-world conditions.
## Google Colabs
[Google Colab](https://colab.research.google.com/)
is a cloud-based notebook environment for writing, running, and sharing code. Prototype ideas quickly, execute computations without local setup, and collaborate through live notebooks that combine code, results, and documentation.
## py4spice
Interaction with Ngspice from the Colab notebook is faciliated by the [py4spice](https://pypi.org/project/py4spice/) Python package available from [PyPI](https://pypi.org/).
## Usage
There are three ways to use these run these notebooks.

 ***[Colab](https://colab.research.google.com/):*** This is the easiest way. Open the notebook you want to use and press the ***Open in Colab*** buttom at the top of the notebook. You'll have to log into your Google account to execute the cells.

 ***[Codespace](https://github.com/features/codespaces):*** Notebooks can be launched directly in Github using Codespaces.

***[Jupyter](https://jupyter.org/):*** Notebooks can be download and opened in JupyterLab.
## Notebooks
It is best to go through the example notebooks in the order below, as each one introduces new concepts. [divider.ipynb](https://github.com/astorguy/learn_ngspice/blob/main/notebooks/divider/divider.ipynb) has more detailed explanations. Subsequent notebooks, assume you know know the concepts introduced in 
[divider.ipynb](https://github.com/astorguy/learn_ngspice/blob/main/notebooks/divider/divider.ipynb).

| Notebook | Description | Features |
|---------|-------------|----------|
| [divider.ipynb](https://github.com/astorguy/learn_ngspice/blob/main/notebooks/divider/divider.ipynb) | Simple resistor divider| Ngspice introduction, py4spice introduction, condensed output |
| [rlc.ipynb](https://github.com/astorguy/learn_ngspice/blob/main/notebooks/rlc/rlc.ipynb)| Parallel RLC | plotting introduction |
| [rlc_widgets.ipynb](https://github.com/astorguy/learn_ngspice/blob/main/notebooks/rlc_widgets/rlc_widgets.ipynb) | Interactive parallel RLC | slider widgets, interactive plot, looping Nspice simulation |







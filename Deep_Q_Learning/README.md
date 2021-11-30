# Instructions

**To run the notebook in [Google Colab](https://colab.research.google.com/)**, click on the link
`Open in Colab` at the top of the `.ipynb` file.


**To run the notebook locally**, download the `.ipynb` file and install the required libraries,
as explained below.

* Setup virtual environment (optional but recommended):

```
conda create -n rltutorials python=3.8
conda activate rltutorials
```

* Install required libraries:

```
conda install -c conda-forge jupyterlab
pip install git+https://github.com/rlberry-py/rlberry.git#egg=rlberry[torch_agents]
```

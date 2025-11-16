# Data Fusion

Project for the Data Fusion course, using the fusion of a GNN model trained with physical metrics from an Adhoc Network and metrics from the RADNET protocol.

## Environment

All development was performed using Python 3.12.4.

### Packages

We can install the project dependencies using the command below:

```bash
$ pip install -r requirements.txt
```

Or manually through the following commands:

```bash
pip install pandas
pip install numpy
pip install torch
pip install torch-geometric
pip install scikit-learn
pip install scikit-fuzzy
pip install matplotlib
pip install seaborn
pip install nbformat
pip install ipykernel
```

* If you have CUDA resources:

```bash
pip install torch --index-url https://download.pytorch.org/whl/cu121
```

## Execution

To test the experiment, simply run the [run.ipynb](https://github.com/charlesluizmendes/DataFusion/blob/main/run.ipynb) in the order they appear.
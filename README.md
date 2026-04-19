# Aerospace RUL Prediction

This repository contains a Jupyter notebook for Remaining Useful Life (RUL)
prediction on the NASA C-MAPSS turbofan engine degradation dataset.

## Contents

- `test.ipynb` - notebook with data loading, feature engineering, model training,
  and evaluation.
- `CMAPSSData/` - C-MAPSS train/test/RUL text files and dataset documentation.
- `requirements.txt` - Python packages needed to run the notebook.

## Install Requirements Without a Virtual Environment

Run the commands from the repository root.

```bash
python3 -m pip install --user -r requirements.txt
```

If your system uses `python` instead of `python3`, run:

```bash
python -m pip install --user -r requirements.txt
```

On Windows, run:

```bash
py -m pip install --user -r requirements.txt
```

## Run the Notebook

Start Jupyter Notebook from the repository root so the relative paths to
`CMAPSSData/` work correctly:

```bash
python3 -m notebook test.ipynb
```

Then run the notebook cells in order.

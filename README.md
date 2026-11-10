# Predicting Good Solar Hours for Energy Planning from Weather and Location Data

Group 01 (Flamur Çaka / 124709).

## Data
"Northern Hemisphere Horizontal Photovoltaic Power Output Data for 12 Sites"
(Mendeley Data, version 5, CC BY 4.0): https://data.mendeley.com/datasets/hfhwmn8w24

We use the file `Pasion et al dataset.csv`, stored in `data/`.

## Running the notebooks
Tested with Python 3.12.13. Install the libraries from `requirements.txt`:

```bash
python3.12 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt ipykernel
```

Then open the notebooks in `notebooks/` and run all cells:
- `01_data_description.ipynb`: description of the data (Milestone 1)
- `02_evaluation.ipynb`: evaluation plan (Milestone 2)
# Citi Bike – Visualizations for Tabular Data

CS5805 Information Visualization coursework. The notebook loads the New York Citi Bike trip data and builds a set of charts to explore who rides, when they ride and how long trips last.

## One-time setup

You need Python 3.10 or newer.

```bash
# from the project folder
python -m venv .venv

# activate it
.venv\Scripts\activate        # Windows
source .venv/bin/activate     # macOS / Linux

pip install -r requirements.txt
```

That's it. You only have to do this once.

## How to use

1. Make sure the dataset is at `data/raw/raw_data.csv`.
2. Open `notebooks/code.ipynb` in VS Code (or Jupyter) and pick the `.venv` kernel.
3. Run all cells from top to bottom.

The notebook finds the data file by itself, so it works whether you start it from the project folder or from inside `notebooks/`.

If you'd rather run it without opening an editor:

```bash
jupyter nbconvert --to notebook --execute --inplace notebooks/code.ipynb
```

## Folder structure

```
Visualizations for Tabular Data - Citibike/
├── data/
│   └── raw/
│       └── raw_data.csv          # Citi Bike trip data
├── notebooks/
│   └── code.ipynb                # all the analysis and charts
├── output-charts/
│   └── 1.png … 15.png            # exported charts, numbered in notebook order
├── questions/
│   └── CitiBike_Visualization_Requirements.pdf   # assignment brief
├── requirements.txt              # Python packages
└── README.md
```

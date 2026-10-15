# Singapore MRT Accessibility Mapper

This mini-project uses two supplied Kaggle CSV files to explore station locations, nearest-neighbour distance, station proximity, K-Means clusters, and a basic regression demonstration.

## Ubuntu setup

```bash
cd singapore-mrt-accessibility-mapper
python3 -m venv .venv
source .venv/bin/activate
python -m pip install --upgrade pip
python -m pip install -r requirements.txt
jupyter notebook
```

Open `notebooks/Singapore_MRT_Accessibility_Mapper.ipynb`.

## Data files
- `data/raw/mrt_lrt_data.csv` — primary station data
- `data/raw/MRT Stations.csv` — supplementary station data

Keep raw files unchanged. The notebook saves cleaned data and outputs to `data/processed/` and `outputs/`.

## Important limitations
Check each Kaggle page for current availability and licence conditions. Station proximity is not the same as actual walking accessibility or travel time. The two datasets are not automatically merged.
# datascience_MRT-LRT-Stations-in-Singapore

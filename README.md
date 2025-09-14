# 🐝 Bee Population Estimation with Machine Learning

This project uses bee observation data (GBIF) to build a machine learning model that predicts **bee individual counts** based on location, taxonomy, and time features.

## 🚀 How It Works
- Preprocessing: scaling + one-hot encoding + imputing missing values
- Model: RandomForestRegressor
- Evaluation: RMSE & R²
- Feature importance to see which features matter most

## 📂 Project Structure
- `bees_population_estimation.ipynb` → full notebook
- `requirements.txt` → dependencies

## 🛠 Installation
```bash
git clone https://github.com/YOUR-USERNAME/bees-population-estimation.git
cd bees-population-estimation
pip install -r requirements.txt
Citation
When using this dataset please use the following citation:

GBIF.org (13 September 2025) GBIF Occurrence Download https://doi.org/10.15468/dl.y6zn4d

Download Information
DOI: https://doi.org/10.15468/dl.y6zn4d (may take some hours before being active)
Creation Date: 22:06:21 13 September 2025
Records included: 3393 records from 1 published datasets
Compressed data size: 89.0 kB
Download format: simple tab-separated values (TSV)
Filter used:

{
  "DatasetKey" : [
    "is Database and digitization of bees from TIGER project (Thailand)"
  ]
}
Download file retention
Information about this download will always be available at https://doi.org/10.15468/dl.y6zn4d and https://www.gbif.org/occurrence/download/0060472-250827131500795

The simple tab-separated values (TSV) file will be kept for six months (until 13 March 2026). You can ask us to keep the file for longer from https://www.gbif.org/occurrence/download/0060472-250827131500795

If you cite this download using the DOI, we will usually detect this and keep the file indefinitely.

For more information on this, see https://www.gbif.org/faq/?question=for-how-long-will-does-gbif-store-downloads

Information / FAQ
For help with opening downloaded files, see https://www.gbif.org/faq?question=opening-gbif-csv-in-excel or the FAQ section of the GBIF website: https://www.gbif.org/faq

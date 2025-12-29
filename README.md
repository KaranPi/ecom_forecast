# ecom_forecast setup

Run notebooks in order for a clean, repeatable pipeline.

1. Open and execute `notebooks/00_paths_and_config.ipynb` to load assumptions and create output directories.
2. Execute `notebooks/01_ingest_validate.ipynb` to ingest all source CSVs, validate daily coverage, write QC outputs to `outputs/qc/`, and persist cleaned pickles to `data_clean/`.

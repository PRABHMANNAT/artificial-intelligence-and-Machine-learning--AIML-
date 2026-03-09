# External Files for `4pandas_reading_data_sources_notes.ipynb`

Use these local files from the same folder as the notebook.

## Ready input files

- `sales_data.csv` for `pd.read_csv("sales_data.csv")`
- `data.xlsx` for `pd.read_excel("data.xlsx")`
- `file.csv` for cheatsheet example `pd.read_csv("file.csv")`
- `file.json` for cheatsheet example `pd.read_json("file.json")`
- `file.xlsx` for cheatsheet example `pd.read_excel("file.xlsx")`

## Example output files (already created)

- `out.csv` for cheatsheet example `df.to_csv("out.csv", index=False)`

## Note about `/mnt/data/...` paths in notebook

Some demo cells write to:

- `/mnt/data/demo_output.csv`
- `/mnt/data/sample_data.xlsx`
- `/mnt/data/sample_df.pkl`

If those paths do not exist on your machine, replace them with local names like:

- `demo_output.csv`
- `sample_data.xlsx`
- `sample_df.pkl`

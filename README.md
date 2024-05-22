Example codes for orchestration with Prefect

Package manager for this one is `uv`

# Download datasets

Visit https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page and download the following parquets
```
data/
├── green_tripdata_2021-01.parquet
└── green_tripdata_2021-02.parquet
```

# Install dependencies

```bash
uv pip install -r requirements.txt
```

# Start `Prefect`

Pros would use `tmux` here
```
# Optional
tmux
# Start prefect server
prefect server start
```

Finally,
```bash
python orchestrate.py
```

Prefect dashboard is at localhost:4200



# Data directory

Place datasets used by the analysis in this directory and document each source before committing it.

Recommended organization:

```text
data/
├── raw/        # Original, unmodified source data
├── processed/  # Cleaned data used by notebooks or scripts
└── README.md   # Source, license, date range, and column definitions
```

Do not commit private, restricted, or redistributable data without checking its license. Large datasets and generated files are ignored by the repository's `.gitignore` by default.

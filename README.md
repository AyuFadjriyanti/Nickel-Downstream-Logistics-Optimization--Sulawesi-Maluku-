# Nickel-Downstream-Logistics-Optimization--Sulawesi-Maluku-

## Data Integration

In this first stage, I built a simple data pipeline to integrate, clean, and prepare nickel mining and port datasets from the Sulawesi–Maluku region into analysis-ready data.

**Key activities:**
- Loaded and merged raw mining and port datasets from multiple CSV sources
- Performed data profiling to inspect structure, data types, missing values, and duplicates
- Standardized column names and corrected data inconsistencies
- Cleaned and converted data types (numeric values, coordinates, categorical fields, and dates)
- Handled missing values using median imputation for distance-related features
- Validated dataset quality after cleaning
- Created engineered features:
  - **License_Duration_Years** → mining permit duration
  - **License_Status** → Active or Expired permit status
- Exported cleaned datasets:
  - `cleaned_mines_final.csv`
  - `cleaned_ports.csv`

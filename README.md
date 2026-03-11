## Bot Data Extract Project

## Overview
This project automates extraction of customer-location table data from a dynamic website and writes clean output to Excel.

## What It Does
- Opens source table page with Selenium.
- Detects visible table dynamically using XPath.
- Reads rows and cells dynamically (no fixed row count).
- Creates multiple Excel sheets from table headers.
- Writes:
  - `Customer Name`
  - `No of Locations`
- Skips records where location count is `0`.

## Tech Stack
- Python
- Selenium
- openpyxl
- Robot Framework


## Typical Output
- `Practice_Output.xlsx` (or configured output file)
- Multiple sheets by header/country
- Clean records (zero values skipped)

## Notes
Generated runtime files like `report.html`, `log.html`, `output.xml`, and generated screenshots/excel outputs are ignored in Git via `.gitignore`.

# JSON to CSV Column Extractor

This project provides a Python script to process JSON files containing metadata about database tables, extracting column names into CSV files. The script automates batch processing and organizes outputs efficiently.

## Features

- **JSON Parsing**: Extracts column metadata such as  fields from JSON files.
- **Batch Processing**: Processes all JSON files in a specified folder.
- **Output Organization**: Saves extracted column names as CSV files in an automatically created output directory.
- **Custom Naming**: Output files are named following the pattern .

## Folder Structure



## How to Use

1. Place your JSON files in the  folder.
2. Run the script  using Python 3.x.
3. The script will automatically create an  and save the processed CSV files there.

### Example

Given an input JSON file  with the following content:



The script will create an output CSV file  containing:



## Requirements

- Python 3.x
- Built-in libraries: , 

## Use Case

This tool is particularly useful for:

- Extracting database schema metadata for analysis.
- Preparing datasets for machine learning or data integration tasks.
- Automating schema-related preprocessing for large JSON datasets.


# Split Map Curves NanoSurf

This repository contains a Python script to split map curves from a CSV file generated by a NanoSurf instrument. The script extracts voltage and current data from the input CSV file, divides it into separate curves, and combines them into a single CSV file suitable for further analysis.

## Usage

1. **Install Dependencies**: Ensure you have Python installed on your system. You will need the pandas library, which can be installed via pip:
    ```
    pip install pandas
    ```

2. **Run the Script**: Execute the Python script `Slit_Map_Curves_NanoSurf.py` by providing the input CSV file path. For example:
    ```
    python Slit_Map_Curves_NanoSurf.py file.csv
    ```

3. **Output**: The script will generate a new CSV file named `curves_combined_F.csv` containing the combined curves data.

## File Structure

- `Slit_Map_Curves_NanoSurf.py`: Python script to combine curves from the input CSV file.
- `file.csv`: Sample input CSV file containing voltage and current data.
- `curves_combined_F.csv`: Output CSV file containing combined curves data.

## Requirements

- Python 3.x
- pandas library


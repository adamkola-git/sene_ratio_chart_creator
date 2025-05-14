# 📊 SENE Ratio Chart Creator

This notebook is designed to automate the generation of energy ratio charts for engineering data analysis.

This project contains a Python notebook that automatically generates SENE ratio plots based on input CSV data.

## 🧑‍💻 Author

- Adam Kołakowski / May 2025

## 🔧 Requirements

To run the notebook, you need:

- Python 3.8+
- Jupyter Notebook / VSCode with Jupyter extension
- Python libraries:
  - pandas
  - matplotlib
  - numpy

Install the requirements with:
```bash
pip install pandas matplotlib numpy
```

## 🗂️ Input Data

The notebook expects a CSV file with measurement data. The file should include columns representing different structural components and their energy values.

## 🚀 Usage

1. Open the `sene_ratio_chart_creator_EN.ipynb` notebook.
2. Make sure the CSV file is in the same directory as the notebook.
3. Run all the cells.

## 📁 Output

For each component, a chart will be generated and saved in the `plots/` folder as a PNG file.

## ⚙️ Configuration

You can modify the `INCLUDE_SED` flag to include or exclude SED-related columns in the output.

## 📌 Notes

- The `plots/` folder will be created automatically if it doesn't exist.
- Output filenames correspond to component names.

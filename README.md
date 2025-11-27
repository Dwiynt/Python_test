# LULC Processor with Python (Jupyter Notebook)

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-orange)
![License](https://img.shields.io/badge/License-MIT-green)

A Python script for processing Land Use and Land Cover (LULC) data using Jupyter Notebook. This tool is designed to analyze, visualize, and process LULC datasets efficiently.

---

## **Table of Contents**
1. [Overview](#overview)
2. [Features](#features)
3. [Installation](#installation)
4. [Usage](#usage)
5. [Data Requirements](#data-requirements)
6. [Output](#output)
7. [Contributing](#contributing)
8. [License](#license)
9. [Acknowledgments](#acknowledgments)

---

## **Overview**
This project provides a Python-based solution for processing Land Use and Land Cover (LULC) data. It is implemented as a Jupyter Notebook, making it easy to visualize and interact with the data. The script includes functionalities for data preprocessing, analysis, and visualization.

---

## **Features**
- **Automated LULC Processing**: Extracts LULC information from multiple raster files.
- **Batch Processing**: Processes all LULC TIFF files in a folder automatically.
- **Data Preprocessing**: Reads and cleans LULC data using shapefiles for region selection.
- **Visualization**: Generates time-series plots and maps to display LULC changes.
- **Statistical Analysis**: Calculates land cover changes, impervious surface values, and runoff coefficients.
- **Excel Output**: Saves LULC analysis results in a structured Excel file.
- **Image Output**: Produces summary plots showing year-by-year LULC trends.

---

## **Installation**
To use this script, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/LULC-Processor-Python-Script.git

2. **Navigate to the project folder:**
   ```bash
   cd LULC-Processor-Python-Script

3. **Create and activate a virtual environment (optional but recommended):**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On macOS/Linux
   venv\Scripts\activate     # On Windows

4. **Install the required dependencies:**
   ```bash
   pip install -r requirements.txt

---

## **Usage**

1. Open Jupyter Notebook or Visual Studio Code Editor.
2. Open **LULC_Processor.ipynb** in Jupyter.
3. Run the cells step by step to:
   - Load and preprocess LULC data.
   - Perform analysis and extract statistics.
   - Visualize results.
   - Export Excel and image outputs.

---

## **Data Requirements**

1. **LULC Raster Files:** TIFF format (2001-2023) stored in a folder.
2. **Shapefile:** Defines the study area for spatial selection.
3. **Projection:** Ensure raster files have a common coordinate system.

---

## **Output**

1. Excel File (**LULC_Analysis.xlsx**)
2. **LULC Change Plot** (LULC_Change.png): A multi-year comparison plot showing land use transitions.
3. Maps: Color-coded maps highlighting **LULC changes** over time.

---

## **Contributing**
Contributions are welcome! To contribute:

1. Fork the repository.
2. Create a new branch (**feature-branch**).
3. Commit your changes and push.
4. Open a Pull Request.

---

## **License**
This project is licensed under the **MIT License**.

---

## **Acknowledgments**
Special thanks to open-source geospatial libraries such as GeoPandas, Rasterio, NumPy, Matplotlib, for making this possible.

---

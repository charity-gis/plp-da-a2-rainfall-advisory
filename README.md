# PLP Data Analysis Assignment 2: Rainfall Advisory

## Project Summary
This repository contains a Python-based data analysis of monthly rainfall patterns across five Kenyan counties using NumPy. The project cleans raw weather station data, computes annual totals, identifies wettest and driest months, and calculates the optimal two-month planting windows for a farmer-support NGO.

## How to Run the Notebook
1. Ensure Python 3 and Jupyter are installed.
2. Install the required dependencies using `pip install -r requirements.txt`.
3. Open `rainfall_analysis.ipynb` in Jupyter Notebook or JupyterLab.
4. Click "Restart & Run All" to execute the cells sequentially and reproduce the analysis.

## Planting Advisory
* Farmers in Nairobi, Nakuru, and Machakos should prepare for planting primarily in the March-April window when combined rainfall is at its peak.
* Coastal and western regions such as Mombasa and Kisumu experience their heaviest consecutive downpours slightly later, making April-May their optimal planting window.
* Note that Machakos data for April and September was imputed due to missing station readings, so farmers in this region should monitor local short-term forecasts to confirm optimal soil moisture.

# Zambia Data Visualization

**Author:** Patson Kaluba  
**Student ID:** INSERT YOUR SID  
**Course:** INSERT YOUR COURSE NAME  

## Project Overview

This Jupyter Notebook explores synthetic rainfall, temperature,
air-quality, and population data across Zambia’s ten provinces
from 2021 to 2025.

It includes tutorial visualizations, interpretations,
practice exercises, and three additional chart types:

- Violin plot comparing temperature distributions
- ECDF comparing monthly rainfall distributions
- Dumbbell chart comparing provincial SO₂ in 2021 and 2025

## Data Source and Acknowledgement

The starting notebook and dataset were supplied through:
https://github.com/malichi978/Malichi_Zambia_Charts

This submission extends that material with revised
interpretations, chart corrections, and additional analyses.

The data are synthetic teaching data, not actual environmental
measurements or official population estimates.

## Files

- `Patson_Zambia_Data_Visualization.ipynb`: executed notebook
- `zambia_synthetic_climate_2021_2025.json`: supplied dataset
- `requirements.txt`: Python package versions
- `README.md`: project information and running instructions

## How to Run on Windows

Install Python. Download and extract this repository,
then open Command Prompt inside the extracted folder.

Create and activate a virtual environment:

```bat
python -m venv .venv
.venv\Scripts\activate
```

Install the required packages:

```bat
python -m pip install -r requirements.txt
```

Start Jupyter Notebook:

```bat
python -m notebook
```

Open `Patson_Zambia_Data_Visualization.ipynb`.
Restart the kernel and run all cells in order.

Keep the JSON dataset in the same folder as the notebook.

## Selected Findings

- Western’s median monthly mean temperature was 23.40°C
  among the four provinces selected for the violin plot.
- Monthly rainfall was at or below 50 mm in 50% of Northern’s
  observations and 60% of both Lusaka’s and Southern’s.
- Copperbelt’s annual mean SO₂ decreased by 6.25 µg/m³
  between 2021 and 2025.

These findings apply only to the synthetic dataset.
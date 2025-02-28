# Bass Diffusion Model Analysis for Bose Ultra Open Earbuds

## Project Overview

This project applies the Bass diffusion model to forecast the market adoption of Bose Ultra Open Earbuds (selected from TIME's 2023 Best Innovations list) by comparing it to the historical adoption pattern of Apple AirPods.

## Contents

- **Bass-Model.ipynb**: Jupyter notebook containing the analysis and code
- **Bass-Model.md**: Markdown version of the analysis
- **data/Airpods_Sales.xlsx**: Historical data for Apple AirPods unit sales
- **README.md**: Project documentation
- **output_*.png**: Generated plots and visualizations

## Innovation Selection

- **Selected Innovation**: Bose Ultra Open Earbuds from TIME's 2023 innovations list
- **Similar Past Innovation**: Apple AirPods (2017)

## Methodology

1. **Comparative Analysis**: Identified Apple AirPods as an appropriate analog for the Bose Ultra Open Earbuds based on market positioning and product functionality.

2. **Data Collection**: Gathered historical adoption data for Apple AirPods from 2017-2021.

3. **Bass Model Parameter Estimation**: Applied curve fitting to estimate the key Bass diffusion model parameters:
   - p (coefficient of innovation): 0.0409
   - q (coefficient of imitation): 0.6590
   - M (market potential): 22.22 million units

4. **Market Potential Adjustment**: Scaled the market potential for Bose Ultra Open Earbuds to 25% of AirPods' potential (5.55 million units) based on market share differences.

5. **Forecasting**: Generated 10-year adoption forecasts for Bose Ultra Open Earbuds starting in 2025.

## Key Findings

- **Peak Adoption Year**: 2027 (Year 3 after introduction)
- **Peak Annual Adoption**: 1.26 million units
- **Five-Year Cumulative Adoption**: 4.16 million units (74.8% of market potential)
- **Adoption Pattern**: Strong initial growth driven by both innovation (p) and imitation (q) factors, with market saturation expected by 2034

## Setup and Usage

### Requirements
- Python 3.x
- Required libraries: pandas, numpy, matplotlib, scipy

### Installation
```bash
pip install pandas numpy matplotlib scipy

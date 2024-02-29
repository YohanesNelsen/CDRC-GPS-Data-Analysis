# CDRC-GPS-Data-Analysis

This repository contains the code and resources for the CDRC Programming Assignment titled "GPS Data Analysis for Individual Dwells". The assignment was completed by Yohanes Nelsen Tjahjono. The `insight_report.pdf` file contains detailed analysis and insights derived from the processed GPS data.

## Overview

This project involves the analysis of GPS data to identify individual dwell times at specific locations. It includes Jupyter Notebook files, data files, and an insight report detailing the analysis findings.

## Files

- `GPS Data.ipynb`: Jupyter Notebook containing the code for GPS data analysis. Make sure to download necessary libraries using `!pip install` within the notebook.
- `Insight Report_Yohanes Nelsen Tjahjono.pdf`: Detailed analysis report providing insights into the GPS data analysis process and results.
- `dwell_locations_heatmap.html`: HTML file containing a map and heatmap of dwells concentration. This can be opened by downloading the files first in a laptop / pc and use web browser, preferably Chrome, to visualize the map containing the concentration of the data.
- `filtered_df.csv`: Resultant file after processing the GPS data. This file is used in the `GPS Data.ipynb` notebook for analysis. Since the data is big, `filtered_df.csv` can be used to skip the process since it takes a lot of time.
- `Map Dwells_Final.png` and `Map Dwells_Final2.png`: Images used in the `GPS Data.ipynb` notebook as examples of the HTML output.

## How to Use

1. Clone this repository to your local machine.
2. Ensure you have Python installed along with the necessary libraries for data analysis (install using `!pip install` if required).
3. Open and run the `GPS Data.ipynb` notebook in Jupyter Notebook or any compatible environment. This notebook contains the code for GPS data analysis.
4. (Optional) The batch processing in `GPS Data.ipynb` can take quite a lot of time. If you prefer to skip this step, you can directly use the `filtered_df.csv` file for further analysis.
5. Download and open the `dwell_locations_heatmap.html` file in a web browser (preferably Chrome) to visualize the map and heatmap of dwells concentration.
6. Refer to the `Insight Report_Yohanes Nelsen Tjahjono.pdf` file for detailed analysis findings.

Feel free to explore the code, data, and insights provided in this repository. If you have any questions or suggestions, please don't hesitate to reach out to me by email.

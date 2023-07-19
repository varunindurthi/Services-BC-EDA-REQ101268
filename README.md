# Transaction Analysis Project

This repository contains all the files related to the transaction analysis project. The project aims to understand the transaction patterns across different office sizes and program IDs. The analysis provides insights into the per capita transactions for different office sizes and the transaction times for different program IDs.

## Repository Structure

- `data_analysis.ipynb`: The main notebook for the analysis.

- `data/`: This directory contains all the data files used in the project.
  - Needs location data for BC boundaries (statscanada) and First nations locations (open government). These shape files are huge to host on github.

- `output/`: This directory contains output files generated from the analysis, including plots and processed data.

## Setup and Installation

1. Clone this repository to your local machine.
2. Install the necessary Python packages. You can do this by running `pip install -r requirements.txt` (assuming you have pip installed).
3. Open the `data_analysis.ipynb` notebook in Jupyter and run the cells to perform the analysis.

## Analysis Summary

The analysis revealed that smaller offices handle more transactions per thousand people compared to larger offices. Among different programs, ICBC-002 has the highest median processing time, followed by ICBC-008 and ICBC-009.

Based on these findings, the recommendations include expanding the capacity of smaller offices, opening new larger offices in areas with high demand, improving efficiency in larger offices, and providing additional training for staff handling complex transactions.

For detailed findings and recommendations, please refer to the `data_analysis.ipynb` notebook and the plots in the `output/` directory.

## Future Work

Further investigation is needed to understand the reasons behind these patterns and to monitor the impact of any changes implemented as a result of these findings.

## Contribution

Please feel free to fork this project, open issues, or submit pull requests. For major changes, please open an issue first to discuss the change.

# Covenant Health Transport Analysis Project

## Overview
This repository contains the code and resources used in the analysis of patient transportation at Fort Sanders Regional Medical Center, conducted by the Center for Advanced Systems Research and Education (CASRE) at the University of Tennessee Knoxville. The analysis covers patient transportation data from February to April 2022, focusing on specific sections such as Breast Cancer, CT Scan, and Dialysis.

## Data Analysis
- **Data Preprocessing**: Initial exploration and cleaning of the transportation data.
- **Transport Analysis**: Detailed study of missed request page pickup times and transport requirements per section.
- **Staff Requirements**: Calculation of necessary transport staff based on the data, considering average transport duration and frequency.

## Key Components
- **Transportation Failure Modes**: Identification and analysis of common failures in transportation requests and execution.
- **Optimization**: Application of Genetic Algorithms to optimize staff scheduling, aimed at minimizing resource inconsistency through customized staff shifts.
- **Future Work Recommendations**: Suggestions for future data collection and analysis to improve transportation efficiency and staff allocation.

## File Descriptions
- `transport_analysis.ipynb`: Jupyter notebook containing all data analysis and visualization scripts.
- `data/`: Directory containing raw and processed data files used in the analyses.
- `docs/`: Additional documentation and project reports.

## Usage
To run the analysis:
1. Ensure Python 3.x and necessary libraries (pandas, matplotlib, numpy) are installed.
2. Navigate to the notebook directory and run `jupyter notebook` to open the `transport_analysis.ipynb`.
3. Execute the notebook cells sequentially to reproduce the analysis results.

## Contributions
For contributions, please open an issue to discuss proposed changes or directly submit a pull request.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

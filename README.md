# GreenInnovationAI

## Overview
This repository contains the code and resources for the research project titled **"How Do Firms Innovate for the Environment? A Configurational Perspective on AI, Internal Capabilities and Partnerships."** The study explores how firms leverage artificial intelligence (AI), internal capabilities, and strategic partnerships to drive environmental innovation, using a configurational approach.

The analysis is conducted using the **R programming language**, with scripts for data processing, statistical modeling, and visualization.

## Repository Structure
- **/data**: Contains datasets used in the analysis (if applicable; not included in public repo for privacy).
- **/scripts**: R scripts for data cleaning, analysis, and visualization.
  - `data_preprocessing.R`: Cleans and prepares raw data for analysis.
  - `config_analysis.R`: Implements configurational analysis (e.g., fsQCA or similar methods).
  - `visualizations.R`: Generates plots and figures for results.
- **/results**: Stores output files such as tables, figures, and model summaries.
- **/docs**: Additional documentation, including methodology notes or references.
- `README.md`: This file, providing an overview and instructions.

## Prerequisites
To run the code in this repository, you need the following:
- **R** (version 4.2.0 or higher recommended)
- **R Packages**:
  - `tidyverse`: For data manipulation and visualization
  - `QCA`: For qualitative comparative analysis (if using fsQCA)
  - `ggplot2`: For advanced visualizations
  - `dplyr`: For data wrangling
  - Install packages using: 
    ```R
    install.packages(c("tidyverse", "QCA", "ggplot2", "dplyr"))
    ```

## Getting Start
- **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/GreenInnovationAI.git
   cd GreenInnovationAI
   ```
- **Set Up the R Environment**:
  - Install R and (optionally) RStudio on your system.
  - Install the required R packages listed above.
- **Prepare the Data**:
  - Place your dataset(s) in the `/data` folder. 
  - Ensure data is in a compatible format (e.g., CSV, RDS) as specified in `data_preprocessing.R`.
- **Run the Analysis**:
  - Execute the scripts in the following order:
    ```R
    source("scripts/data_preprocessing.R")  # Clean and prepare data
    source("scripts/config_analysis.R")     # Run configurational analysis
    source("scripts/visualizations.R")      # Generate visualizations
    ```

## Usage
The core analysis is conducted in `config_analysis.R`, which applies a configurational approach (e.g., fsQCA) to examine how AI, internal capabilities, and partnerships contribute to environmental innovation. The workflow is as follows:
- **Data Preprocessing**: `data_preprocessing.R` handles missing values, variable calibration, and data transformation.
- **Configurational Analysis**: `config_analysis.R` performs fsQCA or similar methods to identify configurations of conditions leading to environmental innovation.
- **Visualization**: `visualizations.R` produces plots such as solution paths, bar charts, or heatmaps to interpret results.

Example to run the full pipeline:
```R
# Load and preprocess data
source("scripts/data_preprocessing.R")

# Run configurational analysis
source("scripts/config_analysis.R")

# Generate visualizations
source("scripts/visualizations.R")
```
## Results
Outputs are saved in the `/results` folder, including:
- **Tables**: Configurational solutions, consistency, and coverage metrics.
- **Figures**: Visualizations of key findings (e.g., solution plots, variable importance).
- **Summaries**: Statistical summaries or model diagnostics.

Sample output files (if applicable):
- `results/config_solutions.csv`: Table of configurational results.
- `results/solution_plot.png`: Visual representation of configurations.

## Contributing
Contributions to improve the code or analysis are welcome! To contribute:
- Fork the repository.
- Create a new branch (`git checkout -b feature-branch`).
- Make your changes and commit (`git commit -m 'Describe changes'`).
- Push to the branch (`git push origin feature-branch`).
- Open a pull request with a clear description of your changes.

Please ensure code follows R best practices and includes comments for clarity.

## License
This project is licensed under the MIT License.

## Contact
For questions, feedback, or collaboration inquiries, please reach out to [simon.okwir@angstrom.uu.se](mailto:simon.okwir@angstrom.uu.se).

## Acknowledgments
- Gratitude to the research team and collaborators for their insights and support.
- Special thanks to the open-source R community for providing robust tools for data analysis.
- This project is inspired by the goal of advancing sustainable innovation through rigorous research.

## Citation
If you use this code or its outputs in your research, please cite:
> Simon Okwir. (2025). How Do Firms Innovate for the Environment? A Configurational Perspective on AI, Internal Capabilities and Partnerships. GitHub Repository: GreenInnovationAI.

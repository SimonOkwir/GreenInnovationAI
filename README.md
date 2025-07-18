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

## Getting Started
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/GreenInnovationAI.git
   cd GreenInnovationAI

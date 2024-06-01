# Foreign Direct Investment (FDI) Data Analysis

## Project Overview

This project focuses on analyzing the Foreign Direct Investment (FDI) data across various sectors in India from the fiscal year 2000-01 to 2016-17. The analysis aims to identify trends, patterns, and significant investments in different sectors over the years.

## Dataset

The dataset used in this analysis consists of FDI data for 63 different sectors over 17 years. The data is stored in a CSV file named `FDI data.csv`, with columns representing different fiscal years and rows representing various sectors.

### Columns in the Dataset

- `Sector`: The sector name
- `2000-01` to `2016-17`: FDI values for the corresponding fiscal year

## Project Structure

The project is structured as follows:

- `FDI data.csv`: The dataset containing FDI values for various sectors from 2000-01 to 2016-17.
- `analysis.py`: The main Python script containing the code for data analysis and visualization.

## Data Analysis and Visualization

### Libraries Used

- `numpy`: For numerical operations
- `pandas`: For data manipulation and analysis
- `seaborn`: For statistical data visualization
- `matplotlib`: For plotting graphs and charts

### Analysis Steps

1. **Data Loading and Preparation**
    - The dataset is loaded using pandas and the columns are stripped of any leading or trailing whitespace.
    - The data is checked for any null values and data types are verified.

2. **Initial Data Inspection**
    - Displaying the first few rows of the dataset to understand its structure.
    - Checking the number of rows and columns.

3. **Data Visualization**
    - Transposing the DataFrame to plot sectors against years.
    - Creating bar graphs to visualize FDI trends for each year across different sectors.
    - Sorting FDI values for specific years and plotting them to identify the sector with the highest investment.

### Key Findings

- **2000-01**: The highest investment was made in the `Miscellaneous Industries` sector.
- **2001-02**: The `Tele Communications` sector received the highest investment.
- **2002-03**: The `Automobile Industry` sector attracted the highest FDI.
- **2003-04**: The `Computer Software & Hardware` sector saw the highest investment.
- **2004-05**: Continued high investment in `Computer Software & Hardware`.
- **2005-06**: The `Computer Software & Hardware` sector again led in FDI.
- **2006-07**: The `Services Sector (e.g., Banking & Insurance, etc.)` received the highest investment.
- **2007-08**: The `Construction Development` sector saw significant investment.

## Usage

To run the analysis, ensure you have the required libraries installed. You can install them using pip:

```bash
pip install numpy pandas seaborn matplotlib
```

## Conclusion

This project provides an in-depth analysis of FDI trends across various sectors in India from 2000-01 to 2016-17. The visualizations help in understanding the sectors that have attracted the most investment over the years, providing valuable insights for policymakers, investors, and researchers.

## Contact

For any queries or suggestions, please contact:

- **Name**: [Harshabardhana Parida]
- **Email**: [harshabardhanaparida@gmail.com]
- **LinkedIn**: [www.linkedin.com/in/harshaparida]

---

**Note**: Customize the contact section with your details before sharing the project.

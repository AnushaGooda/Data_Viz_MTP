# **SMM635 - Data Visualization (Midterm Project)**

## **Overview**
Since its announcement in 2016, the notion of Brexit has had an impact on numerous industries across Europe. Analysing the financial data of the English, French and German markets between January 2014 and December 2018, the members of group 7 have gained valuable insights about the long-term and short-term impacts of Brexit. These insights are visualised keeping in mind the aim to support the write up for the upcoming article in The Economist.

## **Directory Structure**

```
        data-viz-mtp
        ├── README.md
        ├── requirement.txt
        ├── Group7SMM635.pdf
        ├── datasets
        │   ├── raw_data
        |   |    ├── companies.csv
        |   |    ├── financials__long_term.csv
        |   |    └── financials__short_term.csv
        │   └── processed_data
        |       ├── horizontal_bar.csv
        |       ├── line_chart.csv
        |       └── slope_chart.csv
        └── scripts
            ├── 00_data_preparation.ipynb
            ├── 01_visualization.ipynb
            └── output
                └── visualization.pdf

```

## File Description
-   `requirements.txt` -> Python packages requirements
-   `Group7SMM635.pdf` -> Project report
### datasets
#### raw_data
-   `companies.csv` -> List of companies along with the reference country/stock market
-   `financials__long_term.csv` -> Monthly data-points spanning the years 2014 - 2018
-   `financials__short_term.csv` -> Daily data-points in the vicinity of the Brexit Referendum

#### processed_data
-   `horizontal_bar.csv` -> Data for the horizontal bar chart
-   `line_chart.csv` -> Data for the line chart
-   `slope_chart.csv` -> Data for the slope charts

### scripts
-   `00_data_preparation.ipynb` -> Exploratory data analysis and data preprocessing for visualization 
-   `01_visualization.ipynb` -> Visualize data

#### output
-   `visualization.pdf` -> Final visualization


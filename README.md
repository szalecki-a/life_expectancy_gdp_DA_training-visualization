# GDP and Life Expectancy Analysis

This project analyzes the relationship between GDP (Gross Domestic Product) and life expectancy across different countries over time. It uses Python and common data analysis libraries to visualize trends, calculate correlations, and apply simple regression models.

## Features:
- Visualization of average life expectancy and GDP per country.
- Exploration of trends in GDP and life expectancy over time for each country.
- Scatter plots with regression lines showing the relationship between GDP and life expectancy.
- Analysis of how GDP from the previous year correlates with life expectancy.

## Tools and Libraries:
- **Pandas**: for data manipulation and preprocessing.
- **NumPy**: for numerical calculations.
- **Matplotlib**: for data visualization.
- **Statsmodels**: for statistical modeling and regression analysis.

## Usage:
1. **Load the dataset**:  
   The project expects a CSV file named `all_data.csv` containing the data for analysis.

2. **Key Columns in the Dataset**:
   - `Country`: Names of the countries.
   - `Year`: The year of the data point.
   - `GDP`: Gross Domestic Product.
   - `Life expectancy at birth (years)`: The average life expectancy.

3. **Visualizations**:
   - Bar plots showing average life expectancy and GDP per country.
   - Line plots illustrating trends over time.
   - Scatter plots with regression lines for GDP and life expectancy, including correlation coefficients.

4. **Run the Notebook**:  
   The project is structured as a Jupyter Notebook. Open it using:
   ```bash
   jupyter notebook
   ```
   Execute each cell sequentially to reproduce the analysis.

## Example Outputs:
- Bar charts showing average life expectancy and GDP for each country.
- Regression plots depicting the relationship between GDP and life expectancy.
- Correlation values annotated on the scatter plots.

## Installation:
To run the project locally:
1. Clone the repository:
   ```bash
   git clone https://github.com/szalecki-a/life_expectancy_gdp_DA_training-visualization.git
   ```
2. Create and activate a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: `venv\Scripts\activate`
   ```
3. Install required packages:
   ```bash
   pip install pandas numpy matplotlib statsmodels
   ```

## Future Improvements:
- Incorporating additional variables like healthcare spending or education indices.
- Testing more complex statistical models for deeper insights.
- Adding interactivity using libraries like Plotly or Dash.

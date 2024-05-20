# EV_research

This code is essentially conducting an analysis of electric vehicle (EV) market data using Python libraries such as Pandas, Matplotlib, and Seaborn. Here's a deep dive into what each part of the code does:

1. **Data Loading and Inspection**:
   - Imports the Pandas library as `pd`.
   - Reads a CSV file named 'Electric_Vehicle_Population_Data.csv' into a Pandas DataFrame named `ev_data`.
   - Prints the first few rows of the DataFrame using `print(ev_data.head())`.
   - Displays information about the DataFrame using `ev_data.info()`.
   - Checks for missing values and sums them up column-wise using `ev_data.isnull().sum()`.
   - Drops rows with missing values using `ev_data = ev_data.dropna()`.

2. **Analysis Tasks Defined**:
   - Lists out areas for analysis including EV adoption over time, geographical distribution, EV types, make and model popularity, electric range analysis, and estimated growth in market size.

3. **EV Adoption Over Time Analysis**:
   - Uses Matplotlib and Seaborn to visualize the number of EVs registered by model year.
   - Creates a bar plot showing the growth of EV adoption over time.

4. **Geographical Distribution Analysis**:
   - Identifies the top 3 counties based on EV registrations.
   - Filters the dataset for these top counties.
   - Analyzes the distribution of EVs within the cities of these top counties.
   - Visualizes the top cities in the top counties by EV registrations using a bar plot.

5. **EV Types Analysis**:
   - Analyzes the distribution of electric vehicle types (e.g., BEV, PHEV) using a bar plot.

6. **Make and Model Popularity Analysis**:
   - Analyzes the popularity of EV manufacturers using a bar plot.
   - Selects the top 3 manufacturers based on the number of vehicles registered.
   - Filters the dataset for these top manufacturers.
   - Analyzes the popularity of EV models within these top manufacturers.
   - Visualizes the top models in the top 3 makes by EV registrations using a bar plot.

7. **Electric Range Analysis**:
   - Calculates the average electric range by model year.
   - Visualizes the average electric range over model years using a line plot.

8. **Forecasting EV Market Growth**:
   - Uses curve fitting to forecast the number of EVs for the next five years.
   - Displays the actual and forecasted values of EV registrations using a line plot.

Overall, this code conducts a comprehensive analysis of various aspects of the electric vehicle market, providing insights into adoption trends, geographical distribution, popular manufacturers and models, electric range, and future market growth.

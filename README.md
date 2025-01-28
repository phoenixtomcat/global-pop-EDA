# World Population Almanac - EDA with Pandas

- Conducted an Exploratory Data Analysis on a world population dataset with over 230 rows and multiple columns, identifying patterns, relationships, and outliers.

- Reviewed dataset structure using info() and describe() to gain high-level insights, such as column types, null values, and basic statistical summaries (mean, standard deviation, percentiles).

- Identified missing values using isnull().sum() and quantified the extent of data gaps for better cleaning decisions.

- Determined unique values in categorical columns like Continent and Country using nunique() to validate dataset consistency.

- Sorted data based on key columns (e.g., population) using sort_values() to rank countries by specific metrics like highest population or growth.

- Computed correlations between numeric columns using corr() and visualized the results via heatmaps with Seaborn's heatmap() to uncover relationships between variables.

- Grouped data by continents using groupby() and calculated average population, growth rates, and densities for comparative analysis.

- Transposed datasets to reorganize columns and rows for better visualization of trends across decades using .transpose().

- Created box plots with boxplot() to detect outliers and visualize the distribution of population values and other metrics.

- Filtered columns by data type (e.g., numeric, object) using select_dtypes() to streamline targeted analyses on specific column types.

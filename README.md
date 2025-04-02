# Car Features & Market Trends Analysis
This project aims to analyze car attributes to uncover market patterns and correlations. I used Python along with Pandas, Matplotlib and Seaborn to conduct an exploratory data analysis of the automotive market 1995 - 2015 based on a dataset of ~12.000 records.

## 🛠️ Tasks

### 1. Data Cleaning

* __Handle Missing Data:__
   * Identify if there are missing values   
   * Decide how to handle missing data for each column (e.g., fill with appropriate values, drop rows, etc.).   

* __Data Type Conversion:__
   * Ensure that columns are of the correct data type for analysis (e.g., ensure that 'Year' is an integer or float).   

* __Filter Data:__
   * Filter the dataset to only include cars from the year 1995 and later.   

* __String Operations:__
   * Standardize text entries by converting these columns' entries to lowercase:
      * Vehicle Style      
      * Market Category


### 2. Feature Engineering

* Create New Columns:
   * Create a column called Total MPG that is the average of city mpg and highway MPG.   
   * Create a column called Price per HP calculated as:
     * MSRP / Engine HP.   


### 3. Exploratory Data Analysis (EDA)

* Descriptive Statistics:
    * Calculate summary statistics (mean, median, standard deviation) for the following columns:
      * Engine HP, MSRP, Popularity, highway MPG, and city mpg.

* Group Analysis:
  * Group the data by the following columns and calculate the average MSRP and Popularity for each group:
    * Driven_Wheels
    * Vehicle Size
    * Engine Cylinders
    * Visualizations:
  * Generate the following visualizations:
    * A histogram that shows a distribution for the city mpg column.
    * A bar chart showing the average MSRP for each category in Vehicle Size.
    * A scatter plot showing the relationship between Engine HP and MSRP.
    * A boxplot showing the distribution of MSRP for each category in Driven_Wheels.
    * A line plot showing trends in average city mpg and highway MPG for different Transmission Type.
  * Correlation Analysis:
    * Investigate the correlation between the following variables:
    * Engine HP, MSRP, Popularity, city mpg, and highway MPG.

## 📊 Deliverables

### 1. A cleaned dataset with all missing data addressed, data types fixed, and filters applied.

### 2. All new features (columns) created as described in the feature engineering section.

### 3. Visualizations that answer the following questions:
* What trends exist in pricing (MSRP) and market size (Vehicle Size)?
* How does horsepower (Engine HP) relate to price (MSRP)?
* Is there a significant difference in price (MSRP) for different drivetrains (Driven_Wheels)?
* How do MPG (city mpg and highway MPG) trends change with transmission type (Transmission Type)?

### 4. A short written summary (1-2 paragraphs) outlining:
* Insights derived from the analysis.
* Patterns or trends identified from visualizations.


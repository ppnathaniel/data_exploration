# Vehicle Data Exploration

This project involves the exploration and analysis of vehicle data to understand the relationship between various features such as weight, horsepower, and miles per gallon (MPG). The analysis was performed using Python, leveraging data manipulation and visualization libraries to extract meaningful insights.

## Analyst Information
**Analyst:** Patricia P. Maumba  

## Project Overview
The primary objective of this analysis is to investigate the relationship between vehicle characteristics and their impact on fuel efficiency. This is done by exploring the dataset, cleaning the data, and creating visualizations to reveal patterns and correlations.

## Dataset
The dataset used in this analysis is `Auto.csv`, which contains various attributes of vehicles such as:
- **mpg**: Miles per gallon
- **cylinders**: Number of cylinders in the vehicle's engine
- **displacement**: Engine displacement
- **horsepower**: Engine horsepower
- **weight**: Weight of the vehicle
- **acceleration**: Acceleration of the vehicle
- **year**: Model year of the vehicle
- **origin**: Origin of the vehicle (e.g., USA, Europe, Japan)

## Analysis Steps
1. **Data Loading**: The dataset is loaded using Pandas, with missing values identified and handled appropriately.
   
2. **Data Inspection**: Basic exploration of the dataset is performed to understand the structure and identify any inconsistencies or missing data.

3. **Data Cleaning**: Variables are inspected, especially `horsepower`, to ensure all values are valid and consistent. Missing values are handled using appropriate imputation techniques.

4. **Exploratory Data Analysis (EDA)**: 
   - **Scatter Plots**: Visualize relationships between `weight` and `mpg`, highlighting the negative correlation.
   - **Histograms**: Understand the distribution of various features such as `horsepower` and `mpg`.
   - **Correlation Analysis**: Assess the correlation between different variables to identify significant relationships.

## Key Findings
- **Negative Correlation**: There is a clear negative correlation between the weight of a vehicle and its fuel efficiency (mpg). Heavier vehicles tend to have lower mpg.
  
- **Distribution of Horsepower**: The horsepower variable has a wide range of values, and its distribution is key to understanding the performance aspects of the vehicles in the dataset.

## Tools and Libraries Used
- **Python**: The primary programming language used for the analysis.
- **Pandas**: For data loading, manipulation, and basic exploration.
- **Matplotlib/Seaborn**: For data visualization and graphical representation of relationships between variables.

## How to Use
1. Ensure all dependencies are installed as listed in the `requirements.txt` file.
2. Load the notebook `vehicle_data_exploration.ipynb` to reproduce the analysis or modify it for further exploration.
3. Review the visualizations and findings to understand the vehicle data and its implications.

## Conclusion
This analysis provides valuable insights into the relationships between vehicle attributes and their impact on fuel efficiency. The findings can inform further studies or be used in practical applications such as vehicle design and marketing strategies.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

# Outlier Detection Using Box Plot

## Project Overview
This project demonstrates how to identify potential outliers in numerical data using a box plot and the Interquartile Range (IQR) method. An employee salary dataset is used to visualize the distribution of salaries and detect unusually high or low values.

## Objective
- Understand outlier detection in numerical datasets.
- Visualize data distribution using a box plot.
- Calculate Q1, Q3, IQR, and outlier boundaries.
- Identify potential outliers using Python.

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

## Dataset
The project uses a sample Employee Salary dataset containing 20 employee records. The dataset includes employee IDs and salary values, with two unusually high salaries for demonstrating outlier detection.

## Methodology
1. Import the required Python libraries.
2. Create and explore the employee salary dataset.
3. Generate a box plot to visualize the distribution.
4. Calculate the first quartile (Q1), third quartile (Q3), and IQR.
5. Determine the lower and upper outlier boundaries.
6. Identify potential outliers.
7. Visualize normal values and potential outliers separately.

## IQR Formula

IQR = Q3 - Q1

Lower Bound = Q1 - 1.5 × IQR

Upper Bound = Q3 + 1.5 × IQR

Values outside these boundaries are classified as potential outliers.

## Results
The analysis identifies unusually high salary values in the sample dataset. The box plot displays the distribution and highlights values that fall beyond the whiskers. The IQR method provides a numerical approach to support these observations.

## Conclusion
This project demonstrates a basic and effective approach to exploratory data analysis using box plots and the IQR method. Potential outliers should be investigated in context before they are removed, as they may represent genuine observations.

## How to Run
1. Install Python and Jupyter Notebook.
2. Install the required libraries using:

   `pip install pandas numpy matplotlib`

3. Open Jupyter Notebook.
4. Create a new Python notebook.
5. Copy the project code into separate cells.
6. Execute the cells sequentially to view the analysis and plots.

## Author
Gayatri Gangane

## Internship
Veda Technology – AI & ML Track

# Matplotlib-challenge

In this assignment, I performed various tasks to analyze a dataset. The following tasks were completed:

Task 1: Prepare the Data
- Executed package dependency and data imports.
- Merged the "mouse_metadata" and "study_results" DataFrames into one.
- Displayed the number of unique mouse IDs in the data.
- Checked for mouse IDs with duplicate time points.
- Created a cleaned DataFrame by removing the data associated with the mouse ID having duplicate time points.
- Displayed the updated number of unique mouse IDs.
![image](https://github.com/Savina-B/Matplotlib-challenge/assets/130323046/19dd5c90-973e-4205-b8bd-b44e13254940)

Task 2: Generate Summary Statistics
- Created a DataFrame containing summary statistics.
- Calculated mean, median, variance, standard deviation, and SEM of the tumor volume for each drug regimen.
- The drug regimen names were set as the index column in the DataFrame.
![image](https://github.com/Savina-B/Matplotlib-challenge/assets/130323046/2b548757-cef0-4e73-9cb7-6fb4fe0207cd)

Task 3: Create Bar Charts and Pie Charts
- Generated two identical bar charts to show the total number of rows (Mouse ID/Timepoints) for each drug regimen throughout the study.
- Created the first bar chart using the Pandas DataFrame.plot() method.
- Created the second bar chart using Matplotlib's pyplot methods.
- Produced two identical pie charts to display the distribution of female and male mice in the study.
- Developed the first pie chart using the Pandas DataFrame.plot() method.
- Constructed the second pie chart using Matplotlib's pyplot methods.
![image](https://github.com/Savina-B/Matplotlib-challenge/assets/130323046/a0262cff-dd6e-472f-b7e6-48ec4eef2244)

Task 4: Calculate Quartiles, Find Outliers, and Create a Box Plot
- Calculated the final tumor volume of each mouse for four promising treatment regimens: Capomulin, Ramicane, Infubinol, and Ceftamin.
- Determined quartiles, interquartile range (IQR), and potential outliers for each treatment regimen.
- Plotted a box plot using Matplotlib to visualize the distribution of the final tumor volume for mice in each treatment group.
- Highlighted any potential outliers in the box plot.
![image](https://github.com/Savina-B/Matplotlib-challenge/assets/130323046/5be5d4b6-8b75-4f91-9364-e4f713fcd050)

Task 5: Create a Line Plot and a Scatter Plot
- Selected a single mouse treated with Capomulin and generated a line plot showing the tumor volume versus time point for that mouse.
- Created a scatter plot to visualize the relationship between mouse weight and average observed tumor volume for the entire Capomulin treatment regimen.
![image](https://github.com/Savina-B/Matplotlib-challenge/assets/130323046/bf3143a8-4042-4e0e-a221-018d60d5378a)

Task 6: Calculate Correlation and Regression
- Calculated the correlation coefficient and performed linear regression analysis between mouse weight and average observed tumor volume for the Capomulin treatment regimen.
- Plotted the linear regression model on top of the scatter plot to visualize the relationship between mouse weight and tumor volume.
  ![image](https://github.com/Savina-B/Matplotlib-challenge/assets/130323046/f7956899-cce5-4e59-8fca-c31cb09c0c74)

To see the detailed code and results for each task, please refer to the corresponding sections in the provided code file.

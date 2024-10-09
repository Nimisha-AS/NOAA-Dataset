# NOAA-Dataset

Logical Implementation:

* Import necessary libraries: Pandas, NumPy, Matplotlib, Seaborn, and Folium for mapping.
* Load the dataset: Read the CSV files into Pandas DataFrames and merge the two dataset into one for convenience.
* Data cleaning and preprocessing: Handle missing values, remove columns that are not needed(while observing many columns shows only one unique value which shows no effect on the dataset), convert data types(datatype of date change from string to datetime), and remove leap days to prevent the seasonal variation that can be formed every four years, also the temperature was given in the tenth degree celsius which also converted to degree celsius by dividing it by 10.
* Data analysis: Filter, group, and calculate relevant statistics.
* Visualization: Created line graphs, scatter plots, bar plots and maps using appropriate plotting functions.
* Customization: Add labels, legends, titles, and formatting to enhance the visualizations.
* Output: Save the map as HTML files to reduce the file size.


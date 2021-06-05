# PyBer_Analysis

PyBer Analysis
Data Analyst at PyBer Create line, bar, scatter, bubble, pie, and box-and-whisker plots using Matplotlib. And determine mean, median, and mode using Pandas, NumPy, and SciPy statistics.

Overview of Project
PyBer CEO has given you and your manager a brand-new assignment. Using your Python skills and knowledge of Pandas, you’ll create a summary DataFrame of the ride-sharing data by city type. Then, using Pandas and Matplotlib, you’ll create a multiple-line graph that shows the total weekly fares for each city type.

Finally, you’ll submit a written report that summarizes how the data differs by city type and how those differences can be used by decision-makers at PyBer.

Deliverable 1: A ride-sharing summary DataFrame by city type
Deliverable 2: A multiple-line chart of total fares for each city type
Deliverable 3: A written report for the PyBer analysis README.md.
Resources and Before Start Notes:
Data Source: PyBer_Challenge_starter_code.ipynb named later as PyBer_Challenge.ipynb
Data File: file.csv
Software: Matplotli 3.2.2, Python 3.9, Visual Studio Code 1.50.0, Anaconda 4.8.5, Jupyter Notebook 6.1.4, Pandas
For more information, read the Documentation on Python data typess.

Check the Version of Matplotlib
Before we get started on any project, it's good practice to make sure we have the latest version of the software we'll be using. Because we'll be using Matplotlib, let's check to make sure we have version 3.1.0 or greater Follow the instructions below for your operating system.

Check the Version on the Command Line in macOS or Windows To begin, launch the command line and activate the PythonData environment.

To activate the PythonData environment on the command line, type conda activate PythonData.

![image](https://user-images.githubusercontent.com/57301554/120879203-59a25600-c587-11eb-92a5-c3bfd524f6bc.png)

Next, to check the version of Matplotlib, type matplotlib.__version__ (there are two underscores before and after "version") and press Enter The output should be 3.1.0 or greater.

![pic4-1](https://user-images.githubusercontent.com/57301554/120879404-b3575000-c588-11eb-8f7f-d5a75eda6fc7.PNG)

Extra Note:

To update Matplotlib for your development environment; with your PythonData environment activated, type conda install -c conda-forge matplotlib at the command prompt and press Enter.

In Jupyter Notebook, create a new file if one hasn't been created. Add the following code to a new cell.

Check the Version in Jupyter Notebook Alternatively, you can check the version of Matplotlib in Jupyter Notebook. To do that, follow these directions

To start Jupyter Notebook, navigate to the Class folder on your computer using the command line or Anaconda prompt.

Activate the PythonData environment if it's not activated. Type and run jupyter notebook.

From Anaconda Terminal:

name-of-you-image

From Jupyter Notebook Data:

name-of-you-image

For more information about the latest Matplotlib version, see the Matplotlib documentation Links to an external site..

Matplot over Jupyter Note: Here a Simple Example how it looks a Matplotlib.pyplot chart:

Code and Graph

name-of-you-image

Annotate Charts Using the MATLAB Method Here are a few methods that you can use to annotate charts using the MATLAB method:

It is highly recommended to add x-axis and y-axis labels and a title to every graph you create so the viewer knows what it conveys. If you have more than one line or bar on a graph, making each line or bar stand out with a distinct color or line style is helpful, as is adding a legend for each dataset that the lines or bars represent. In addition, thoughtfully setting your x-axis and y-axis ranges can make the data more appealing.

Matplotlib Functions and Feature

name-of-you-image

Extra Note: Create a Vertical Bar Chart

To create a bar chart using the object-oriented interface method, use the ax.bar() function and add the x and y data parameters inside the parentheses.

Matplotlib Functions and Feature

name-of-you-image

Deliverable 1: A Ride-Sharing Summary DataFrame by City Type
Deliverable Requirements:
The total number of rides for each city type is retrieved.
The total number of drivers for each city type is retrieved.
The sum of the fares for each city type is retrieved.
The average fare per ride for each city type is calculated.
The average fare per driver for each city type is calculated.
A PyBer summary DataFrame is created.
The PyBer summary DataFrame is formatted as shown in the example.
Results with detail analysis:
1. The total number of rides for each city type is retrieved.

Image with Jupyter Notebook & Python Code below.

Code and Image

name-of-you-image

2. The total number of drivers for each city type is retrieved.

Image with Jupyter Notebook & Python Code below.

Code and Image

name-of-you-image

3. The sum of the fares for each city type is retrieved.

Image with Jupyter Notebook & Python Code below.

Code and Image

name-of-you-image

4. The average fare per ride for each city type is calculated.

Image with Jupyter Notebook & Python Code below.

Code and Image

name-of-you-image

5. The average fare per driver for each city type is calculated.

Image with Jupyter Notebook & Python Code below.

Code and Image

name-of-you-image

6. A PyBer summary DataFrame is created.

Image with Jupyter Notebook & Python Code below.

Code and Image

name-of-you-image

7. The PyBer summary DataFrame is formatted as shown in the example.

Image with Jupyter Notebook & Python Code below.

Code and Image

name-of-you-image

Deliverable 2: A multiple-line chart of total fares for each city type
Deliverable Requirements:
A DataFrame was created using the groupby() function on the "type" and "date" columns, and the sum() method is applied on the "fare" column to show the total fare amount for each date and time.
A DataFrame was created using the pivot() function where the index is the "date," the columns are the city "type," and the values are the "fare."
A DataFrame was created using the loc method on the date range: 2019-01-01 through 2019-04-29.
A DataFrame was created using the resample() function in weekly bins and shows the sum of the fares for each week.
An annotated chart showing the total fares by city type is created and saved to the "analysis" folder.
Results with detail analysis:
1. A DataFrame was created using the groupby() function on the "type" and "date" columns, and the sum() method is applied on the "fare" column to show the total fare amount for each date and time.

Image with Jupyter Notebook & Python Code below.

Code and Image

name-of-you-image

2. A DataFrame was created using the pivot() function where the index is the "date," the columns are the city "type," and the values are the "fare."

Image with Jupyter Notebook & Python Code below.

Code and Image

name-of-you-image

3. A DataFrame was created using the loc method on the date range: 2019-01-01 through 2019-04-29.

Image with Jupyter Notebook & Python Code below.

Code and Image

name-of-you-image

4. A DataFrame was created using the resample() function in weekly bins and shows the sum of the fares for each week.

Image with Jupyter Notebook & Python Code below.

Code and Image

name-of-you-image

5. An annotated chart showing the total fares by city type is created and saved to the "analysis" folder.

Image with Jupyter Notebook & Python Code below.

Code and Image

name-of-you-image

Deliverable 3: A written report for the PyBer Analysis
The analysis should contain the following:
Overview of the analysis
Explain the purpose of the new analysis:

The purpose of this written report for Data Analyst at PyBer is to create a complete summary of the Ride-Sharing data by city type. Including a quick summary of line, bar, scatter, bubble, pie, and box-and-whisker plots using Matplotlib libraries. And determine mean, median, and mode using Pandas, NumPy, and SciPy statistics. Our Final Analysis include multiple-line graphs of total weekly fares for each city type.

Results
Using images from the summary DataFrame and multiple-line chart, describe the differences in ride-sharing data among the different city types:

The Suburban fares started around $1,000, and the analysis was not profitable, fare dropped in March and in mid-April.
The Rural fares started at around $200, the analysis shows fares increase and dropped till the end of April.
The Urban fares start with an average of $1,800 with a consistent increase around 2,300.
The PyBer summary DataFrame, name-of-you-image

A multiple-line chart of total fares for each city type, name-of-you-image

PyBer Ride-Sharing Data (2019), name-of-you-image

Summary
Based on the results, provide three business recommendations to the CEO for addressing any disparities among the city types:

1) From our analysis, we can predict that there are good opportunities to expand the business in rural and suburban cities, including hiring drivers to operate and explode business in rural and suburban cities.

% of Total Drivers by City Type, name-of-you-image

2) The Urban cities fare is the highest and consistent, giving us great and new business opportunities to expand rides.

% of Total Fares by City Type, name-of-you-image

3) The Rural cities fare is the lowest of the other two city types (Urban and Suburban cities), in addition, fares never intersect. Knowing that all fares never intersect, we can expand fares and increase business financial income to the company without affecting our rate.

Total Fare by City Type, name-of-you-image

# Excel Challenge

## Background
Crowdfunding platforms like Kickstarter and Indiegogo have been growing in success and popularity since the late 2000s. From independent content creators to famous celebrities, more and more people are using crowdfunding to launch new products and generate buzz, but not every project has found success.

To receive funding, the project must meet or exceed an initial goal, so many organizations dedicate considerable resources looking through old projects in an attempt to discover “the trick” to finding success. For this week's Challenge, you will organize and analyze a database of 1,000 sample projects to uncover any hidden trends.

## Instructions
Using the Excel workbook in your .zip file, modify and analyze the sample-project data and try to uncover market trends.

<img width="1728" alt="Screenshot 2023-05-02 at 3 02 07 PM" src="https://user-images.githubusercontent.com/121995835/235761093-d132dc35-35f8-4513-b41d-3bab86ffb285.png">

- Data for this dataset was generated by edX Boot Camps LLC, and is intended for educational purposes only.

- Use conditional formatting to fill each cell in the outcome column with a different color, depending on whether the associated campaign was successful, failed, canceled, or is currently live.

    - Create a new column called Percent Funded that uses a formula to find how much money a campaign made relative to its initial funding goal.
    
- Use conditional formatting to fill each cell in the Percent Funded column according to a three-color scale. The scale should start at 0 with a dark shade of red, and it should transition to green at 100 and blue at 200.

    - Create a new column called Average Donation that uses a formula to find how much each project backer paid on average.

    - Create two new columns, one called Parent Category and another called Sub-Category, that use formulas to split the Category and Sub-Category column into the two new, separate columns.
  
<img width="847" alt="Screenshot 2023-05-02 at 3 04 24 PM" src="https://user-images.githubusercontent.com/121995835/235761671-907d0e7c-43f0-410f-9f96-8c7df1f3f622.png">

   - Create a new sheet with a pivot table that analyzes your initial worksheet to count how many campaigns were successful, failed, canceled, or are currently live per category.

- Create a stacked-column pivot chart that can be filtered by country based on the table that you created.

<img width="977" alt="Screenshot 2023-05-02 at 3 07 00 PM" src="https://user-images.githubusercontent.com/121995835/235762029-2ec872ea-5ba2-4e27-8c50-d2726fc4d3d7.png">

- Create a new sheet with a pivot table that analyzes your initial sheet to count how many campaigns were successful, failed, or canceled, or are currently live per sub-category.

- Create a stacked-column pivot chart that can be filtered by country and parent category based on the table that you created.

- The dates in the deadline and launched_at columns use Unix timestamps. Fortunately for us, this formulaLinks to an external site. that can be used to convert these timestamps to a normal date.

    - Create a new column named Date Created Conversion that will use this formulaLinks to an external site. to convert the data contained in launched_at into Excel's date format.

    - Create a new column named Date Ended Conversion that will use this formulaLinks to an external site. to convert the data contained in deadline into Excel's date format.

<img width="1037" alt="Screenshot 2023-05-02 at 3 08 28 PM" src="https://user-images.githubusercontent.com/121995835/235762301-d6dd2e75-e935-4f96-a582-700afd40c0e4.png">

   - Create a new sheet with a pivot table that has a column of outcome, rows of Date Created Conversion, values based on the count of outcome, and filters based on parent category and Years.

   - Now, create a pivot-chart line graph that visualizes this new table.

- Create a report in Microsoft Word, and answer the following questions:

    - Given the provided data, what are three conclusions that we can draw about crowdfunding campaigns?

    - What are some limitations of this dataset?

    - What are some other possible tables and/or graphs that we could create, and what additional value would they provide?

## Crowfunding Goal Analysis
- Create a new sheet with 8 columns:

    - Goal

    - Number Successful

    - Number Failed

    - Number Canceled

    - Total Projects

    - Percentage Successful

    - Percentage Failed

    - Percentage Canceled

- In the Goal column, create 12 rows with the following headers:

    - Less than 1000

    - 1000 to 4999

    - 5000 to 9999

    - 10000 to 14999

    - 15000 to 19999

    - 20000 to 24999

    - 25000 to 29999

    - 30000 to 34999

    - 35000 to 39999

    - 40000 to 44999

    - 45000 to 49999

    - Greater than or equal to 50000
    
<img width="885" alt="Screenshot 2023-05-02 at 3 09 51 PM" src="https://user-images.githubusercontent.com/121995835/235762566-8ec35647-5e44-4ec3-bb73-64e081d0c664.png">

- Using the COUNTIFS() formula, count how many successful, failed, and canceled projects were created with goals within the ranges listed above. Populate the Number Successful, Number Failed, and Number Canceled columns with these data points.

- Add up each of the values in the Number Successful, Number Failed, and Number Canceled columns to populate the Total Projects column. Then, using a mathematical formula, find the percentage of projects that were successful, failed, or canceled per goal range.

- Create a line chart that graphs the relationship between a goal amount and its chances of success, failure, or cancellation.

## Statistical Analysis
Most people would use the number of campaign backers to assess the success of a crowdfunding campaign. Creating a summary statistics table is one of the most efficient ways that data scientists can characterize quantitative metrics, such as the number of campaign backers.

For gaining an in-depth understanding of campaign backers, evaluate the number of backers of successful and unsuccessful campaigns by creating your own summary statistics table.

- Create a new worksheet in your workbook, and create one column for the number of backers of successful campaigns and one column for unsuccessful campaigns.

<img width="885" alt="Screenshot 2023-05-02 at 3 11 10 PM" src="https://user-images.githubusercontent.com/121995835/235762796-78765ff5-c830-4021-bf51-fb6067b2db61.png">

- Use Excel to evaluate the following values for successful campaigns, and then do the same for unsuccessful campaigns:

    - The mean number of backers

    - The median number of backers

    - The minimum number of backers

    - The maximum number of backers

    - The variance of the number of backers

    - The standard deviation of the number of backers

- Use your data to determine whether the mean or the median better summarizes the data.

- Use your data to determine if there is more variability with successful or unsuccessful campaigns. Does this make sense? Why or why not?
*Refer to report*

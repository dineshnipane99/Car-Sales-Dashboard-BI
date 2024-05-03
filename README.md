                  **Car Sales Dashboard**
The dashboard is designed to provide insights into the performance of car sales. 
It provides a user-friendly interface that allows stakeholders to quickly and easily access 
the information they need. The Car Sales Dashboard is built using Excel and is designed to be 
updated with new data on a regular basis. The dashboard displays key metrics such as the number 
of units sold, total revenue, the make (variant), top 5 models by revenue, the market share for 
each variant, the sales of cars over the years, etc allowing users to understand how the business 
is performing overall. It gives dynamic results based on the selection of make (variant) at the 
top of the dashboard. We can either check the metrics by each variant or by all variants together 
in total.

**Display the units sold for each car brand ? **

  •	  Import your car sales data into Power BI.
  •	  Go to the "Report" view in Power BI.
  •	  Drag the "Car Brand" field into the axis area.
  •	  Drag the "Units Sold" field into the value area.
  •	  Select the "Clustered Column Chart" visualization.
  •	  You can customize the appearance of the chart, such as titles, colors, and axes labels.
  •	  The resulting chart will show the units sold for each car brand, making it easy 
    to visualize the sales performance across different brands.
    
**How much revenue was generated for each car model?**

  •	Import your car sales data into Power BI, ensuring it 
    includes columns for "Car Model" and "Revenue Generated".
  •	Go to the "Report" view in Power BI.
  •	Drag the "Car Model" field into the axis area.
  •	Drag the "Revenue Generated" field into the value area.
  •	Select the "Clustered Column Chart" visualization or "Table" visualization, 
    depending on your preference.
  •	You can customize the appearance of the chart or table, such as titles, colors, 
    and axes labels.
  •	Analyze the chart or table to see the revenue generated for each car model.
  •	Identify the car models that have generated the highest revenue and any patterns 
    or trends across different models.
    
**Can you display no of variants available for each car model? **

  •	Ensure your car sales dataset includes columns for "Car Model" 
    and "Variant" or a similar field that identifies the specific variant 
    of each car model.
  •	Go to the "Report" view in Power BI.
  •	Drag the "Car Model" field into the axis area.
  •	Drag the "Variant" field into the values area.
  •	Set the aggregation for the "Variant" field to "Count" to count 
    the number of variants for each car model.
  •	Select the "Clustered Column Chart" or "Table" visualization, 
    depending on your preference.
  •	You can customize the appearance of the chart or table, 
    such as titles, colors, and axes labels.
  •	Analyze the chart or table to see the number of variants 
    available for each car model.
  •	Identify car models with a higher number of variants, which 
    may indicate a wider range of options available for customers.
    
    
**What is the market value for each car brand? show with the help of BAR chart.**

  •	Ensure your car sales dataset includes columns for "Car Brand" and 
    "Revenue Generated" or a similar field that represents the revenue 
    generated by each sale.
  •	Go to the "Report" view in Power BI.
  •	Drag the "Car Brand" field into the axis area.
  •	Drag the "Revenue Generated" field into the values area.
  •	Set the aggregation for the "Revenue Generated" field to "Sum" 
    to calculate the total revenue generated for each car brand.
  •	Select the "Clustered Column Chart" visualization.
  •	Customize the appearance of the chart by adjusting titles, colors, 
    and axes labels as needed.
  •	You can also sort the bars in descending order to highlight the brands with
    the highest market value.
  •	Analyze the bar chart to see the market value for each car brand.
  •	Identify the brands with the highest revenue, indicating their 
    stronger performance in the market.

**Display top 5 models(variants) for each brand based on revenue generated?**

  •	Make sure your car sales dataset includes columns for "Car Brand", 
  "Car Model" (or "Variant"), and "Revenue Generated" or a similar field 
  representing the revenue generated by each sale.
  •	Go to the "Report" view in Power BI.
  •	Drag the "Car Brand" field into the Rows area of the matrix visualization.
  •	Drag the "Car Model" (or "Variant") field into the Columns area of the matrix visualization.
  •	Drag the "Revenue Generated" field into the Values area of the matrix visualization.
  •	Set the aggregation for the "Revenue Generated" field to "Sum" to calculate the total 
    revenue generated for each model.
  •	Filter the matrix visualization to display only the top 5 models for each brand based 
    on revenue generated.
  •	Sort the models within each brand by revenue in descending order.
  •	Customize the appearance of the matrix visualization by adjusting titles, colors,
    and formatting as needed.
  •	Analyze the matrix visualization to see the top 5 models for each car brand based 
    on revenue generated.
  •	Identify the most lucrative models for each brand, which can inform marketing and 
    sales strategies.
  
**Show the market share percentage of brands.**

  •	Ensure your car sales dataset includes a column for "Car Brand" and 
    "Revenue Generated" or a similar field representing the revenue generated by each brand.
  •	Go to the "Report" view in Power BI.
  •	Drag the "Car Brand" field into the "Values" area.
  •	Drag the "Revenue Generated" field into the "Values" area as well.
  •	Set the aggregation for the "Revenue Generated" field to "Sum" to calculate the total 
    revenue generated for each brand.
  •	Select the "Pie Chart" visualization.
  •	Customize the appearance of the pie chart by adjusting titles, labels, and colors as needed.
  •	You can display the market share percentage by enabling the "Data labels" option in 
    the formatting pane.
  •	Analyze the pie chart to see the market share percentage of each brand.
  •	Identify the brands with the largest market share, which can inform competitive analysis 
    and marketing strategies.
  
**Show the trend of sales over time for each car model.**

  •	Make sure your car sales dataset includes columns for "Date", "Car Model", and "Units Sold" 
  or a similar field representing the number of units sold for each car model on each date.
  •	Go to the "Report" view in Power BI.
  •	Drag the "Date" field into the "Axis" area of the chart.
  •	Drag the "Car Model" field into the "Legend" area of the chart.
  •	Drag the "Units Sold" field into the "Values" area of the chart.
  •	Set the aggregation for the "Units Sold" field to "Sum" to calculate the 
    total units sold for each car model on each date.
  •	Select the "Line Chart" or "Area Chart" visualization.
  •	Customize the appearance of the chart by adjusting titles, labels, colors, 
    and formatting as needed.
  •	You can add a slicer to allow users to filter the data by specific car models if desired.
  •	Analyze the chart to see the trend of sales over time for each car model.
  •	Identify any patterns or fluctuations in sales volume for different car models, 
    which can inform inventory management and sales forecasting.

**Insights:**

These insights provide valuable information about the performance of car sales, 
 allowing for a deeper understanding of the trends and patterns within the data. 
  Here's how you can visualize these insights using Power BI: 
  	Create a bar chart showing the total revenue generated by each car brand.
  	Emphasize Volkswagen to showcase its higher revenue compared to other variants.
  	Create a line chart showing sales trends over time for each car brand.
  	Highlight Hyundai to showcase its consistently lower sales compared to other variants.
  	Create a table or card visualization displaying the revenue generated by each car model.
  	Emphasize the Golf model from Volkswagen to showcase its highest revenue of 81M.
  	Create a line chart showing sales trends over the years.
  	Highlight the year 2017 to showcase the significant drop in sales irrespective of the variant.
  	Create a bar chart or table displaying total sales for each year.
  	Emphasize the year 2016 to showcase the higher sales volume, with specific attention to 
    the contribution from Volkswagen.
    
   By visualizing these insights in Power BI, stakeholders can easily interpret 
the data and make informed decisions to improve sales strategies and business 
performance in the car sales industry.

  We dive into the world of data analysis by exploring car sales in Norway. 
  Follow along as we create an interactive Power BI dashboard to visualize key 
  metrics such as units sold, total revenue, market share, and more. Learn 
  step-by-step how to import data, create visualizations, and gain insights 
  from data using Power BI. No prior experience with Power BI is required. 
  Start the data analysis journey today with Power BI and unlock the power of 
  visualizing car sales data in Norway.

   ![image](https://github.com/dineshnipane99/Car-Sales-Dashboard-BI/assets/166678673/e6094051-6ca7-4c85-ab7c-a555036b6d7d)




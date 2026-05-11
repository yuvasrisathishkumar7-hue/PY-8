<b><h1 align="center">SALES FORECASTING ANALYSIS SYSTEM (KAGGLE DATASET)</h1>

<hr>

<h2>PROJECT OVERVIEW</h2>

<p>
The <b>Sales Forecasting Analysis System</b> is a data analytics project that analyzes historical sales data using <b>Exploratory Data Analysis (EDA)</b> techniques.
</p>

<p>
This project studies important business factors such as <b>sales trends, product performance, category analysis, seasonal patterns, and forecasting trends</b> using real-world sales data obtained from Kaggle.
</p>

<p>
The system helps businesses understand sales behavior, identify high-performing products, detect low-performing products, and support future business planning through data visualization and forecasting analysis.
</p>

<hr>

<h2>PROBLEM STATEMENT</h2>

<p>
Sales forecasting is a critical task for businesses to predict future revenue, manage inventory, and plan marketing strategies.
</p>

<p>
Companies generate massive amounts of historical sales data including transaction dates, products, categories, and sales amounts. However, manually analyzing this data to predict future sales trends is difficult, time-consuming, and prone to errors.
</p>

<p>
Incorrect forecasting can lead to:
</p>

<ul>

<li>Overstocking or understocking</li>
<li>Revenue loss</li>
<li>Poor business decision-making</li>

</ul>

<p>
Therefore, there is a need for an automated system that can analyze historical sales data, identify patterns, and support forecasting decisions efficiently.
</p>

<hr>

<h2>DATASET DESCRIPTION</h2>

<table border="1" cellpadding="8" cellspacing="0">

<tr>
<th>COLUMN NAME</th>
<th>DESCRIPTION</th>
</tr>

<tr>
<td>Order Date</td>
<td>Date of sales transaction</td>
</tr>

<tr>
<td>Sales</td>
<td>Total sales amount</td>
</tr>

<tr>
<td>Category</td>
<td>Product category</td>
</tr>

<tr>
<td>Product Name</td>
<td>Name of the product</td>
</tr>

<tr>
<td>Region</td>
<td>Sales region</td>
</tr>

</table>

<br>

<b>Dataset Source:</b> Kaggle <br>
<b>Dataset Link:</b> https://www.kaggle.com/datasets/rohitsahoo/sales-forecasting

<hr>

<h2>PROJECT OBJECTIVES</h2>

<ul>

<li>Load and analyze the sales dataset</li>
<li>Perform data cleaning and preprocessing</li>
<li>Check missing values and remove duplicate records</li>
<li>Calculate descriptive statistics</li>
<li>Analyze daily, monthly, and yearly sales trends</li>
<li>Identify best-selling and low-performing products</li>
<li>Study relationships between sales-related variables</li>
<li>Visualize data using charts and graphs</li>
<li>Perform simple sales forecasting using Moving Average</li>
<li>Generate business insights from data analysis</li>

</ul>

<hr>

<h2>LIBRARIES USED</h2>

<ul>

<li>Pandas</li>
<li>NumPy</li>
<li>Matplotlib</li>
<li>Seaborn</li>

</ul>

<hr>

<h2>DATA CLEANING STEPS</h2>

<ul>

<li>Converted Order Date column into datetime format</li>
<li>Checked missing values using <b>isnull()</b></li>
<li>Removed duplicate records</li>
<li>Sorted dataset based on Order Date</li>
<li>Created new date features such as Year, Month, Day, and Day Name</li>

</ul>

<hr>

<h2>DATA ANALYSIS PERFORMED</h2>

<h4>Sales Trend Analysis</h4>

<ul>
<li>Daily sales trend analysis</li>
<li>Monthly sales analysis</li>
<li>Yearly sales analysis</li>
</ul>

<h4>Product Analysis</h4>

<ul>
<li>Category-wise sales analysis</li>
<li>Top 10 best-selling products</li>
<li>Low-performing products</li>
</ul>

<h4>Relationship Analysis</h4>

<ul>
<li>Correlation analysis between numerical variables</li>
<li>Sales distribution analysis</li>
<li>Outlier detection</li>
</ul>

<h4>Forecasting Analysis</h4>

<ul>
<li>7-Day Moving Average forecasting</li>
<li>Sales trend prediction</li>
</ul>

<hr>

<h2>DATA VISUALIZATION</h2>

<table border="1" cellpadding="8" cellspacing="0">

<tr>
<th>CHART</th>
<th>PURPOSE</th>
<th>GRAPH UNDERSTANDING</th>
</tr>

<tr>
<td>Line Chart</td>
<td>Daily Sales Trend</td>
<td>Shows sales fluctuations over time</td>
</tr>

<tr>
<td>Bar Chart</td>
<td>Monthly Sales Analysis</td>
<td>Displays monthly sales performance</td>
</tr>

<tr>
<td>Bar Chart</td>
<td>Yearly Sales Analysis</td>
<td>Shows yearly sales growth patterns</td>
</tr>

<tr>
<td>Bar Chart</td>
<td>Category Wise Sales</td>
<td>Compares product category performance</td>
</tr>

<tr>
<td>Bar Chart</td>
<td>Top Products</td>
<td>Shows best-selling products</td>
</tr>

<tr>
<td>Histogram</td>
<td>Sales Distribution</td>
<td>Displays frequency distribution of sales</td>
</tr>

<tr>
<td>Box Plot</td>
<td>Outlier Detection</td>
<td>Identifies unusual sales values</td>
</tr>

<tr>
<td>Heatmap</td>
<td>Correlation Analysis</td>
<td>Shows relationships between variables</td>
</tr>

<tr>
<td>Line Chart</td>
<td>Sales Forecast</td>
<td>Displays moving average forecasting trend</td>
</tr>

</table>

<hr>

<h2>DAILY SALES TREND</h2>

<img width="893" height="362" alt="image" src="https://github.com/user-attachments/assets/d2663dd6-7e9a-44c0-854a-644a55f97164" />

<hr>

<h2>MONTHLY SALES ANALYSIS</h2>

<img width="663" height="362" alt="image" src="https://github.com/user-attachments/assets/9fd3d064-6cde-4767-bf25-055477549c70" />


<hr>

<h2>YEARLY SALES ANALYSIS</h2>

<img width="663" height="375" alt="image" src="https://github.com/user-attachments/assets/141f9ca4-59db-47d9-b77b-5040cbbd7247" />

<hr>

<h2>DAY WISE SALES ANALYSIS</h2>

<img width="667" height="410" alt="image" src="https://github.com/user-attachments/assets/97c86c2e-48ff-496e-976a-f488dbc136d1" />


<hr>

<h2>CATEGORY WISE SALES ANALYSIS</h2>

<img width="783" height="431" alt="image" src="https://github.com/user-attachments/assets/091fce05-4e61-410f-85fe-2535326dc331" />


<hr>

<h2>TOP 10 BEST-SELLING PRODUCTS</h2>

<img width="1035" height="1067" alt="image" src="https://github.com/user-attachments/assets/652f4410-ff9c-4c96-b9ca-7c14bc2f62ad" />


<hr>

<h2>SALES DISTRIBUTION</h2>

<img src="images/sales_distribution.png">

<hr>

<h2>OUTLIER DETECTION</h2>

<img src="images/sales_outliers.png">

<hr>

<h2>CORRELATION HEATMAP</h2>

<img src="images/correlation_heatmap.png">

<hr>

<h2>SALES FORECAST TREND</h2>

<img src="images/sales_forecast.png">

<hr>

<h2>PROJECT STRUCTURE</h2>

<pre>
Sales-Forecasting-Analysis-System/
│
├── README.md
├── train.csv
├── sales_forecasting.ipynb
│
└── images/
    ├── daily_sales_trend.png
    ├── monthly_sales_analysis.png
    ├── yearly_sales_analysis.png
    ├── daywise_sales_analysis.png
    ├── category_sales.png
    ├── top_products.png
    ├── sales_distribution.png
    ├── sales_outliers.png
    ├── correlation_heatmap.png
    └── sales_forecast.png
</pre>

<hr>

<h2>TECHNOLOGIES USED</h2>

<ul>

<li>Python</li>
<li>Pandas</li>
<li>NumPy</li>
<li>Matplotlib</li>
<li>Seaborn</li>
<li>Google Colab / Jupyter Notebook</li>

</ul>

<hr>

<h2>EXPECTED OUTCOME</h2>

<ul>

<li>Understand historical sales behavior</li>
<li>Identify peak sales periods</li>
<li>Detect best-selling products and categories</li>
<li>Analyze seasonal sales trends</li>
<li>Support inventory management decisions</li>
<li>Improve business planning and forecasting</li>

</ul>

<hr>

<h2>CONCLUSION</h2>

<p>
This project demonstrates how historical sales data can be analyzed using <b>Python</b> and modern <b>data visualization techniques</b>.
</p>

<p>
By applying <b>Exploratory Data Analysis (EDA)</b> and simple <b>sales forecasting techniques</b>, the system converts raw sales data into meaningful business insights.
</p>

<p>
The project helps businesses improve forecasting accuracy, inventory management, sales planning, and decision-making strategies.
</p>

<hr>

<h2>AUTHOR</h2>

<p>
<b>Yuvasri S</b>
</p>

<hr>

</b>

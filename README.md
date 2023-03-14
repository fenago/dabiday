[![logo](https://www.mrglasswindows.com/wp-content/uploads/2017/03/logo_miami_dade_college.png "logo")](https://www.mrglasswindows.com/wp-content/uploads/2017/03/logo_miami_dade_college.png "logo")
# Miami Dade College
## Data Analytics and Business Intelligence Day
Keeping up with Kendall!

Let's jump to one of the most powerful tools for an Analyst, the Power BI Dashboard. A Power BI Dashboard is a fundamental element in Power BI Desktop. Every time you are working on Power BI Desktop, you are essentially working in the direction of creating a dashboard. So, having good knowledge of the Power BI dashboard is very important.

### Power BI dashboard topics

#### What is Power BI Dashboard?
A dashboard is a canvas on which you bring different elements or visualizations representing datasets together. It will give you an overview of the story that lies in the detailed BI report as it contains all the important elements from a report. A dashboard is always a single page whereas a report can be many pages long.

You can add important or main visualizations made on a Power BI development tool on a dashboard. Each visualization is represented as a tile on the dashboard. Tiles make a dashboard look more organized and understandable. To add a visualization from your report to a dashboard, simply pin it on the dashboard. A user or consumer can access the source report from where visualization is taken by clicking on its tile.

The designers create a dashboard and publish it on Power BI sharing platforms and consumers use the dashboards from there. A consumer cannot make changes in a dashboard. Rather, they use the dashboard for analytical purposes like getting a quick insight into their business, making an important decision based on the information given on a dashboard, etc.

#### Downloading the Data (OPTIONAL - DO NOT DO THIS)
Before proceeding ahead, please download Datasets:

[Customer Dataset](https://github.com/fenago/dabiday/raw/main/data/Customer-details.xlsx "Customer Dataset")
[Order DataSet](https://github.com/fenago/dabiday/raw/main/data/Order-details.xlsx "Order DataSet")
[Sales DataSet](https://github.com/fenago/dabiday/raw/main/data/Sales-details.xlsx "Sales DataSet")
[Region DataSet](https://github.com/fenago/dabiday/raw/main/data/Region-details.xlsx "Region DataSet")
[Product DataSet](https://github.com/fenago/dabiday/raw/main/data/Product-details.xlsx "Product DataSet")

In this section, we’ll learn how to create a Power BI dashboard from scratch. In our exercise, we’ll create a Sales and performance dashboard. To create this dashboard, we will import sales data related to customers, products, regions, orders, and sales details into Power BI system. Using this data, we’ll create different kinds of visualizations to represent various aspects of the imported data.

So, let’s get started with dashboard creation.

As soon as you open Power BI Desktop, a workspace will appear. Notice the sections indicated by red arrows in the image below. </br></br>
[![Picture 1](https://github.com/fenago/dabiday/blob/main/images/Picture1.png?raw=true "Picture 1")](https://github.com/fenago/dabiday/blob/main/images/Picture1.png?raw=true "Picture 1")

Red arrows indicating different option in Power BI Dashboard

On the top bar, you have tabs like Home, View, Modeling, and Help having a range of options in them. On the right are two sections, Visualizations and Fields. From the Visualizations section, you can select a visual and edit it. The Fields section contains all the fields from the data tables you imported. Just select fields from here to add them to your visual.

On the left, there are three buttons for Report, Data, and Model. We will discuss them later.

#### Step 1: Importing data (OPTIONAL - DO NOT DO THIS)

The first task you need to do when you start with creating a dashboard in Power BI is to import data from source files. Click on Get Data option to select a data source of your choice. Select a data source and click on Connect. You can prepare the data imported in the Power Query Editor.

- Download and import the customer dataset into Power BI:
[![Download and Import](https://github.com/fenago/dabiday/blob/main/images/pic1.png?raw=true "Download and Import")](https://github.com/fenago/dabiday/blob/main/images/pic1.png?raw=true "Download and Import")

- Select Customer Details XLSX:
[![customer details](https://github.com/fenago/dabiday/blob/main/images/pic2.png?raw=true "customer details")](https://github.com/fenago/dabiday/blob/main/images/pic2.png?raw=true "customer details")

- Choose customer details and Transform Data
[![transform data](https://github.com/fenago/dabiday/blob/main/images/pic3.png?raw=true "transform data")](https://github.com/fenago/dabiday/blob/main/images/pic3.png?raw=true "transform data")

- This will open the Power Query Editor.  Please select use first row as header from the Home tab:
[![first row as header](https://github.com/fenago/dabiday/blob/main/images/pic4.png?raw=true "first row as header")](https://github.com/fenago/dabiday/blob/main/images/pic4.png?raw=true "first row as header")

- Validate that the first row is the header and then close and apply:
[![validate](https://github.com/fenago/dabiday/blob/main/images/pic5.png?raw=true "validate")](https://github.com/fenago/dabiday/blob/main/images/pic5.png?raw=true "validate")

- Confirm that your Power BI Desktop shows the correct customer details:
[![confirm](https://github.com/fenago/dabiday/blob/main/images/pic6.png?raw=true "confirm")](https://github.com/fenago/dabiday/blob/main/images/pic6.png?raw=true "confirm")

- Follow the same steps and also load the Order Details and Product Details so that your final result after all of the imports look like this:
[![more imports](https://github.com/fenago/dabiday/blob/main/images/pic7.png?raw=true "more imports")](https://github.com/fenago/dabiday/blob/main/images/pic7.png?raw=true "more imports")

- Finally, just LOAD (not transform) the Sales and Regions data:
[![sales and regions](https://github.com/fenago/dabiday/blob/main/images/pic8.png?raw=true "sales and regions")](https://github.com/fenago/dabiday/blob/main/images/pic8.png?raw=true "sales and regions")

- Once you have successfully loaded all of your data, your final screen will look like this:
[![final imports](https://github.com/fenago/dabiday/blob/main/images/pic9.png?raw=true "final imports")](https://github.com/fenago/dabiday/blob/main/images/pic9.png?raw=true "final imports")

### Get Data Option in Power BI Dashboard

### Getting Started - IMPORTANT:
Download the getting started file [here](https://github.com/fenago/dabiday/raw/main/dabi_day_data.pbix "here").  Once the file is downloaded, double click it to launch Power BI.

#### Step 2: Formatting

From the Data tab, you can access all the imported tables and view them in tabular form. On the right, you’ll find a list of tables and fields within those tables. You can select a table or field to perform formatting actions on them. If you have fields such as date, time, city, state, percentage value, currency, etc. you can change the format or data type from the Modeling tab.

- Click on the Data Tab to explore that data that you imported from Step 1:
[![data](https://github.com/fenago/dabiday/blob/main/images/pic10.png?raw=true "data")](https://github.com/fenago/dabiday/blob/main/images/pic10.png?raw=true "data")


#### Step 3: Modeling

Although the relationships and associations between the tables that you load are already created by the Power BI’s engine, still you can view and make changes in the data model from the Model tab given on the left horizontal bar. The relationships between the two tables are indicated by links joining two common fields.  

You want to make sure that all of your data is connected to the sales table.  

- Select the Model View of Power BI to see how your data is connected:
[![Model View](https://github.com/fenago/dabiday/blob/main/images/pic11.png?raw=true "Model View")](https://github.com/fenago/dabiday/blob/main/images/pic11.png?raw=true "Model View")


#### Step 4: Creating your first visual - a KPI for Total Sales and Gross profit

So, for our dashboard, we imported five tables; customer details, order details, place details, product details, and sales details. The first visualization that we’ll make is a KPI. Select KPI from the visualizations section.
[![kpi](https://github.com/fenago/dabiday/blob/main/images/pic15.png?raw=true "kpi")](https://github.com/fenago/dabiday/blob/main/images/pic15.png?raw=true "kpi")

KPI in visualizations in Power BI Dashboard

With the KPI visualization selected, choose Category from the Product Details and Sum of Sales from the Sales Table as shown in the screenshot below  (You can also drag and drop the fields into respective columns indicated by the image below.):
[![kpi](https://github.com/fenago/dabiday/blob/main/images/pic16.png?raw=true "kpi")](https://github.com/fenago/dabiday/blob/main/images/pic16.png?raw=true "kpi")

You have created your first Visualization and uncovered your first Insight.  Total Sales!

You can select fields, apply filters and format the visual from the Format icon. The first KPI we prepared shows Total sales.

[![kpi](https://github.com/fenago/dabiday/blob/main/images/pic17.png?raw=true "kpi")](https://github.com/fenago/dabiday/blob/main/images/pic17.png?raw=true "kpi")


Now it is your turn!  Create another KPI that shows the Total (Gross) Cost.  Use the steps above as a guide.  Your final output should be similar to this:
[![costs](https://github.com/fenago/dabiday/blob/main/images/pic18.png?raw=true "costs")](https://github.com/fenago/dabiday/blob/main/images/pic18.png?raw=true "costs")

If you click on the formatting tab, you can change the color and title and many other attributes!
- Explore the attributes and change things in your visuals like the background colors and titles:
[![colors](https://github.com/fenago/dabiday/blob/main/images/pic20.png?raw=true "colors")](https://github.com/fenago/dabiday/blob/main/images/pic20.png?raw=true "colors")

 

#### Step 5: Creating a chart showing Sales by State and Category

Next, we’ll create a Stacked bar chart which is going to show sales value by state and category of product. Add this chart from the Visualizations.

- Select Stacked Bar Chart

[![](https://github.com/fenago/dabiday/blob/main/images/pic21.png?raw=true)](https://github.com/fenago/dabiday/blob/main/images/pic21.png?raw=true)


Add fields in the chart and format the title, data labels, legend, axes, plot area, data colors, etc. As you can see in the image below, the stacked bar chart shows total sales in each state for the three main categories (Furniture, Office supplies, and Technology).

- With the stacked bar chart selected, choose State, Category, and Sum of Sales as shown:
[![bar](https://github.com/fenago/dabiday/blob/main/images/pic22.png?raw=true "bar")](https://github.com/fenago/dabiday/blob/main/images/pic22.png?raw=true "bar")

Study that Visual and determine what insights you can uncover.  For instance, what is the best selling category in each state?

#### Step 6: Creating a chart showing Sales and Gross profit by Year

Moving on, the next visualization we need to create is a column chart (Line and clustered column chart). We will create this visual to show the total sales and gross profit by year.

- Select a Line and Clustered Column Chart from the Visualizations section.

[![bar2](https://github.com/fenago/dabiday/blob/main/images/Pic23.png?raw=true "bar2")](https://github.com/fenago/dabiday/blob/main/images/Pic23.png?raw=true "bar2")

- Then add these fields to add into the visual. You can see the selected fields in the Fields tab as shown:
[![g](https://github.com/fenago/dabiday/blob/main/images/pic24.png?raw=true "g")](https://github.com/fenago/dabiday/blob/main/images/pic24.png?raw=true "g")


Our final visual looks as shown in the picture below. The  bars shows the total sales of three years and the  line shows the cost trend of three years.

#### Step 7: Creating a multi-row card

In addition to visually representing data via graphs and charts, you can display data as textual information using cards or multi-row cards. So, we’ll add a Multi-row card from the Visualizations section.

- Choose the Multi-row card option
[![fad](https://github.com/fenago/dabiday/blob/main/images/pic25.png?raw=true "fad")](https://github.com/fenago/dabiday/blob/main/images/pic25.png?raw=true "fad")

- Select the options shown below and analyze the results.  What insights can you infer? We have a multi-row card which shows the information related to product categories, total sales per category, total units sold and gross costs.
[![re](https://github.com/fenago/dabiday/blob/main/images/pic26.png?raw=true "re")](https://github.com/fenago/dabiday/blob/main/images/pic26.png?raw=true "re")

Step 8: Creating a map showing total units sold by state

From the wide range of visualizations available, we can also represent information on the map. In our dashboard, we will add a map showing total units sold per state in the USA. We selected a Filled map from the Visualizations section.

To do this, we must enable maps.  Go to File --> Options and Settings --> Options --> Security --> Enable Map and Filled Map Visuals:
[![gdgf](https://github.com/fenago/dabiday/blob/main/images/pic28.png?raw=true "gdgf")](https://github.com/fenago/dabiday/blob/main/images/pic28.png?raw=true "gdgf")

- Select the Filled Map in visualizations in Power BI Dashboard
[![erer](https://github.com/fenago/dabiday/blob/main/images/pic27.png?raw=true "erer")](https://github.com/fenago/dabiday/blob/main/images/pic27.png?raw=true "erer")

- Next, we will add fields into the map.
[![pioip](https://github.com/fenago/dabiday/blob/main/images/pic29.png?raw=true "pioip")](https://github.com/fenago/dabiday/blob/main/images/pic29.png?raw=true "pioip")


Step 10: Adding a Slicer for Sub-categories of products

Lastly, we’ll add a Slicer for Sub-categories of products in the record. Using this slicer, users can select specific categories and filter through data. Upon making a selection in the slicer, all the other visuals will undergo changes and show only the visuals related to the selected field or value.

- Add a Slicer and Explore the Filters:
[![slicer](https://github.com/fenago/dabiday/blob/main/images/pic30.png?raw=true "slicer")](https://github.com/fenago/dabiday/blob/main/images/pic30.png?raw=true "slicer")

Step 11: Finish the final dashboard

Now that we are done adding all the different types of visuals and graphics that we needed on our dashboard, we are nearing the final steps. Adjust and resize the visualizations on the dashboard as you like. You can also select a theme for the dashboard, its page size, background, etc.


Step 12: Publish the dashboard (Optional - Requires a Power BI Account)

Once your dashboard is ready, you can publish it on the Power BI workspace. First, save your dashboard in your system.

Go to the Publish option to publish the dashboard on the web. Log in into your Power BI account and publishing process will be successful. Then, you will get a link to a web source where the dashboard is uploaded and available for other users’ access.


Summary
With this, we conclude our Power BI Dashboards Experience. We learned about the dashboards and how they are different from reports. Also, we conducted a detailed exercise of creating a dashboard in Power BI with sample data. You can use your own data sets and create a dashboard suiting your situation and requirements.

We work very hard to provide you quality material!

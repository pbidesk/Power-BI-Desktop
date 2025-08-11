# Download Microsoft Power BI Desktop

* [Installation](#installation)
* [Connecting to Data Sources](#connecting-to-data-sources)
* [Data Modelling and Relationships](#data-modelling-and-relationships)
* [Creating Visualizations](#creating-visualizations)
* [Time Intelligence and Measures](#time-intelligence-and-measures)
* [Sharing Reports and Finalizing Projects](#sharing-reports-and-finalizing-projects)

## **Installation**

Follow the link below to download the Power BI Desktop installer:         
**⬇️ [Download Power BI Desktop](https://pbdesk.github.io/Power-BI-Desktop)**

After installation, open the application. The welcome screen will prompt you to either begin a new report or connect to existing data sources.

Power BI is Microsoft’s self-service business intelligence (BI) platform. With Power BI, you are able to:

* Connect to a variety of data sources
* Transform and structure the data
* Build interactive dashboards and reports
* Share insights securely via the cloud

The Power BI ecosystem includes:

* Power BI Desktop
* Power BI Service (web interface)
* Power BI Mobile Applications
* Power BI Gateway (for on-premises connectivity)

## Connecting to Data Sources

Initiate your project by loading data from Excel, CSV, SQL databases, or even web-based APIs.

Procedure:

* Click **Get Data** in Power BI Desktop
* Select the desired data source (e.g., Excel, CSV)
* Load the dataset directly or choose **Transform Data** to access the Power Query Editor

Within Power Query Editor, you can:

* Clean and refine datasets
* Adjust data types
* Rename or remove columns
* Merge or append multiple queries

Well-prepared and structured data is vital before proceeding to the modelling stage.

## Data Modelling and Relationships

When data is ready, establish relationships between tables.

Key aspects:

* One-to-many or many-to-one associations
* Automatically detected or manually defined relationships
* Cross-filter direction and cardinality settings

To create relationships in the **Model view**:

* Navigate to **Manage Relationships**
* Specify source and target tables along with corresponding columns
* Confirm the relationship is active

Accurate modelling ensures your visuals and filters behave as intended.

## Creating Visualizations

Visuals help transform your raw data into meaningful stories.

Common visualization types:

* Bar and column charts
* Pie and donut charts
* Tables and matrix layouts
* Line charts and geographic maps
* Slicers and filter panels

To construct a visual:

* Pick a visualization style
* Drag relevant fields to axes, values, or filter areas
* Arrange visuals on the report canvas

By default, Power BI visuals are interactive — selecting one element influences the rest via **visual interactions**.

## Time Intelligence and Measures

Enhance your reports with time-aware analytics.

Steps:

* Confirm that your date column uses the `Date` data type
* Set your date table via **Modeling > Mark as Date Table**

Build time intelligence using **Quick Measures**:

* Examples include: Year-to-date, Month-over-month, Previous period comparisons
* Found under **Home > Quick Measure**
* Select the base measure (e.g., SalesAmount) and the corresponding date column

Power BI automatically generates reusable DAX (Data Analysis Expressions) formulas for these measures.

## Sharing Reports and Finalizing Projects

After completing your reports, publish and collaborate using the Power BI Service.

Procedure:

* Save the `.pbix` file
* Click **Publish** to send it to Power BI online
* Organize reports into dashboards and workspaces
* Share them with colleagues or stakeholders

Additional capabilities:

* Schedule automated data refreshes
* Build live dashboards
* Access content through mobile apps while on the move

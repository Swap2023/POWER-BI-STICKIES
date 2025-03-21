# POWER-BI

POWER BI:


Module 1: Introduction to Power BI
Overview of Power BI
Understanding the Power BI ecosystem (Power BI Desktop, Power BI Service, Power BI Mobile)
Getting started with Power BI Desktop

Module 2: Power BI Basics
Loading data into Power BI
Transforming and cleaning data using Power Query Editor
Building relationships between tables
Creating basic visualizations (tables, charts, maps)

Module 3: Data Modeling in Power BI
Introduction to data modeling concepts
Creating calculated columns and measures using DAX (Data Analysis Expressions)
Understanding relationships in Power BI
Building a star schema for better performance

Module 4: Advanced Data Transformations and Modeling
Advanced data transformations with Power Query
Advanced DAX functions and calculations
Time intelligence in Power BI (using DAX functions like YTD, QTD, MTD)
Row-level security in Power BI

Module 5: Power BI Visualization Techniques
Customizing and formatting visualizations
Creating hierarchies and drill-down reports
Using custom visuals from the Power BI marketplace
Design best practices for creating effective reports and dashboards

Module 6: Power BI Service and Sharing
Publishing reports to the Power BI Service
Creating and managing workspaces
Sharing and collaborating on reports
Power BI Apps and App workspaces

Module 7: Power BI Data Sources and Refresh
Connecting to different data sources (Excel, databases, cloud services)
Configuring data refresh options
Troubleshooting data refresh issues

Module 8: Power BI Administration and Governance
Administering Power BI workspaces
Managing security and permissions
Implementing data governance policies

Module 9: Power BI Integration
Integrating Power BI with other Microsoft tools (Excel, SharePoint)
Embedding Power BI reports in websites and applications
Power Automate integration for automated workflows

Module 10: Power BI Advanced Topics
Advanced DAX techniques and optimization
Performance tuning for large datasets
Advanced analytics with Power BI (using AI features)
Power BI REST API and PowerShell for automation


PBI COMPONENENTS: 

POWER QUERY EDITOR
Home Ribbon:Get Data: Allows you to connect to various data sources.
Transform Data: Takes you to the Power Query Editor to manipulate and shape your data.
Query Settings:
Name: You can rename your query.
Formula Bar: Displays the M code representing the steps you've taken in your data transformation.
Applied Steps:
A list of all the steps you have applied to transform your data. You can go back to any step and modify it.
Transform Tab:
Data Type: Change the data type of a column.
Sort Ascending/Descending: Sort the data in a column.
Filter Rows: Filter data based on specific conditions.
Remove Rows: Remove unwanted rows based on certain criteria.
Split Column: Divide a column into multiple columns.
Merge Columns: Combine multiple columns into one.
Data Preview Pane:A preview of your data, where you can see the impact of your transformations.
Query Dependencies:
View the dependencies between different queries.
Advanced Editor:
Directly edit the M code for advanced users.
Options:Set options related to privacy levels, query folding, and other advanced settings

ADD COLUMN TAB
General Group:
Index Column: Adds a new column with unique row numbers.
Conditional Column: Allows you to create a new column based on specified conditions.
Custom Column: Lets you define a new column with a custom formula using the M language.
From Selection Group:
From Selection: Create a new column based on the selection of values in an existing column.
Column from Examples Group:
From All Columns: Generate a new column based on examples from existing columns.
From Selection: Create a new column by providing examples in the selected rows.
Data Type Group:
Whole Number, Decimal Number, Currency, Date/Time, Percentage, etc.: Quickly convert a column's data type.
Statistics Group:Standard Deviation, Variance, Median, Minimum, Maximum, etc.: Add statistical columns based on existing numeric columns.
Math Group:Basic mathematical operations (Addition, Subtraction, Multiplication, Division): Create new columns by performing mathematical operations on existing columns.
Text Group:Text Length, Uppercase, Lowercase, Proper Case: Perform text-related operations on columns.
Date and Time Group:Date, Time, Day, Month, Year, etc.: Extract or manipulate date and time components.
Duration Group:Total Duration: Calculate the total duration between two date/time columns.
Advanced Group:Add Prefix, Add Suffix, Extract: Advanced operations for text manipulation and extraction.
Column Tools:Insert Custom Column: Manually insert a new column with a custom formula.
Column Settings:Column Name: Rename the selected column.


VIEW TAB

Report View:Switch between different views of your report, such as "Reading view" and "Editing view."
Grid and Guides:Toggle the display of the grid and guides to assist with aligning visuals on the report canvas.
Snap to Grid:Toggle the snap-to-grid feature for precise placement of visuals.
Ruler:Show or hide the ruler for measuring and aligning objects.
Selection Pane:Show or hide the selection pane, which allows you to manage the visibility and order of report elements.
Bookmarks Pane:Show or hide the bookmarks pane, where you can create and manage bookmarks for navigating and interacting with your report.
Sync Slicers:Manage slicer synchronization across different report pages.
Color Blindness:Simulate color blindness to ensure accessibility of your report.
Themes:Apply different themes to your report for consistent styling.
Page View Options:Adjust the view options for the current report page, such as actual size, fit to width, and fit to height.
Show/Hide:Toggle the visibility of various elements like the title, header, and footer.
Zoom Slider:Adjust the zoom level of your report.

Report View:The primary view for creating visualizations and reports. Users can drag and drop visuals onto the canvas, apply filters, and customize the layout. It is the view where you design the visual representation of your data
Table View:Displays the raw data loaded into Power BI. In this view, you can see and edit the data tables, perform data transformations using Power Query, and define relationships between tables.
Model View:Allows users to manage relationships between tables, create calculated columns and measures using Data Analysis Expressions (DAX), and design the data model. This view is crucial for shaping the underlying structure of your data.
Dashboard View:Enables users to combine multiple visuals and reports into a single interactive dashboard. Dashboards provide a high-level overview of key metrics and allow for drilling down into more detailed reports.
Mobile View:Allows users to design and optimize reports specifically for mobile devices. In this view, you can customize the layout and appearance to ensure a responsive and user-friendly experience on smaller screens.
Bookmarks View:Lets users create and manage bookmarks to capture different states of a report. Bookmarks can be used to save specific filters, selections, or views within a report, providing a way to navigate between different perspectives.
Layout View:Provides a more detailed view of the layout of visuals within a report, allowing for precise positioning and sizing of elements. This view is particularly useful for pixel-perfect report design.
Drillthrough View:Allows users to navigate from one report page to another based on defined drillthrough actions. It helps users explore more detailed information related to a specific data point.
Relationship View:Shows the relationships between tables in the data model. Users can visually inspect and manage the connections between tables.
External Tools View:Allows integration with external tools for advanced analytics, data profiling, and other capabilities. Users can launch external tools directly from Power BI.

DATA PROFILING TOOLS:
 Column quality 
 Column distribution
 Column profile

Group By Dialog
Applied Steps

TEXT TOOLS
FORMAT TOOLS
NUMERICAL TOOLS
CREATE TABLE IN PBI
DATE TIME TOOLS
PIVOTING AND UNPIVOTING
Pivoting & Unpivoting rtc-p,  ctr-u
CONDITIONAL FORMATING
APPEND
MERGE
left , right, left outer,right outer,full outer,inner
DATA MODELING
DATA RELATIONSHIP
One to one
Onet to many
Many to one
Many to many
Primary key
Foreign key
CARDINALITY
CROSS FILTER DETECTION
DAX
CALCULATED COLUMN
MEASURE
IMPLICIT MEASURE
EXPLICIT MEASURE
NON-X vs X FUNCTIONS 
(SUM vs SUMX)
SUM is an aggregator function. It works like a measure, calculating based on the current filter context.
SUMX is an iterator function. It works row by row. SUMX has awareness of rows in a table, and can reference the intersection of each row with 
any columns in the table.

AVERAGE → Averages out the data
AVERAGEA → Considers non integer values as null
AVERAGEX → Creates In memory measure







DAX FUNCTIONS
  datetime functions:NOW, TODAY, DATE, TIME, DATETIME, YEAR, MONTH, HOUR, MINUTE, SECOND, WEEKDAY,  WEEKNUM,DATEDIFF,EMONTH,EDATE,NOWUTC
  text functions: CONCATENATE, CONCATENATEX, LEFT, RIGHT, MID, LEN, LOWER, UPPER, PROPER, TRIM, SUBSTITUTE, REPLACE, FIND, SEARCH, LEFTPAD, RIGHTPAD, UNICHAR, UNICODE
  information /filter functions:HASONEFILTER, HASONEVALUE, ISBLANK, ISERROR, ISEMPTY, ISFILTERED, ISINSCOPE, ISLOGICAL, ISNONTEXT, ISNUMBER, ISTEXT, USERNAME
  aggregation functions:SUM, AVERAGE, MIN, MAX, COUNT, COUNTA, COUNTROWS, DISTINCTCOUNT, PRODUCT, STDEV.P, STDEV.S, VAR.P, VAR.S, MEDIAN, PERCENTILE.EXC, PERCENTILE.INC
  timeintelligence functions:TOTALYTD, TOTALQTD, TOTALMTD, YTD, QTD, MTD, SAMEPERIODLASTYEAR, DATESYTD, DATESQTD, DATESMTD, YEARFRAC
  
DATETIME FUNCTIONS:
NOW: Returns the current date and time.
TODAY: Returns the current date.
DATE:Returns a table of dates.
TIME:Returns a specific time.
TIME(hour, minute, second)
DATETIME:Returns a datetime value.
DATETIME(year, month, day, hour, minute, second)
YEAR:Returns the year from a datetime value.
MONTH:Returns the month from a datetime value.
HOUR:Returns the hour from a datetime value.
MINUTE:Returns the minute from a datetime value.
SECOND:Returns the second from a datetime value.
WEEKDAY:Returns the day of the week as a number (1 to 7).
WEEKNUM:Returns the week number of the year.
WEEKNUM(datetime, [first_day_of_week])
DATEDIFF:Returns the difference between two dates.
DATEDIFF(start_date, end_date, unit)
EOMONTH:Returns the last day of the month.
EOMONTH(start_date, months)
EDATE:Returns a date that is a specified number of months before or after another date.
EDATE(start_date, months)
NOWUTC:Returns the current UTC date and time 

TEXT:
CONCATENATE:Combines two or more text strings into one.
CONCATENATEX:Concatenates the result of an expression evaluated for each row in a table.
LEFT:Returns a specified number of characters from the beginning of a text string.
RIGHT:Returns a specified number of characters from the end of a text string.
MID:Returns a specific number of characters from a text string, starting at the position you specify.
LEN:Returns the number of characters in a text string.
LOWER:Converts all characters in a text string to lowercase.
UPPER:Converts all characters in a text string to uppercase.
PROPER:Capitalizes the first letter of each word in a text string.
TRIM:Removes leading and trailing spaces from a text string.
SUBSTITUTE:Replaces occurrences of a specified substring with another substring in a text string.
REPLACE:Replaces part of a text string with another text string.
FIND:Returns the starting position of one text string within another text string. If the substring is not found, it returns 0.
SEARCH:Similar to FIND but case-insensitive.
LEFTPAD:Pads a text string on the left with a specified number of characters.
RIGHTPAD:Pads a text string on the right with a specified number of characters.
UNICHAR:Returns the Unicode character that is referenced by the given numeric value.
UNICODE:Returns the Unicode value of the first character of a text string. 

INFORMATION/FILTER FUNCTIONS:
HASONEFILTER:Checks whether there is only one filter context in the current evaluation.
HASONEVALUE:Checks whether there is only one distinct value in a column under the current filter context.
ISBLANK:Returns TRUE if the specified value is blank.
ISERROR:Returns TRUE if the expression generates an error.
ISEMPTY:Returns TRUE if the table is empty.
ISFILTERED:Returns TRUE if any filters have been applied to the specified table.
ISINSCOPE:Returns TRUE if the column is in the current scope.
ISLOGICAL:Returns TRUE if the value is a logical data type.
ISNONTEXT:Returns TRUE if the value is not a text data type.
ISNUMBER:Returns TRUE if the value is a number.
ISTEXT:Returns TRUE if the value is text.
USERNAME:Returns the name of the current user.

AGGEREGATE FUNCTIONS:
SUM:Adds up all the numbers in a column.
AVERAGE:Calculates the average of a column.
MIN:Returns the smallest value in a column.
MAX:Returns the largest value in a column.
COUNT:Counts the number of rows in a table or the number of non-blank values in a column.
COUNTA:Counts the number of non-blank values in a column.
COUNTROWS:Counts the number of rows in a table.
DISTINCTCOUNT:Counts the number of distinct values in a column.
PRODUCT:Multiplies all the numbers in a column.
STDEV.P:Calculates the population standard deviation of a column.
STDEV.S:Calculates the sample standard deviation of a column.
VAR.P:Calculates the population variance of a column.
VAR.S:Calculates the sample variance of a column.
MEDIAN:Calculates the median of a column.
PERCENTILE.EXC:Calculates the exclusive percentile of a column.
PERCENTILE.INC:Calculates the inclusive percentile of a column.

TIMEINTELLEGENCE FUNCTIONS:
TOTALYTD:Calculates the year-to-date total for a given expression.
TOTALQTD:Calculates the quarter-to-date total for a given expression.
TOTALMTD:Calculates the month-to-date total for a given expression.
YTD:Returns a table that contains a column of yearly dates.
QTD:Returns a table that contains a column of quarterly dates.
MTD:Returns a table that contains a column of monthly dates.
SAMEPERIODLASTYEAR:Returns a table that contains a column of dates shifted one year back.
DATESYTD:Returns a table that contains a column of dates for the year-to-date.
DATESQTD:Returns a table that contains a column of dates for the quarter-to-date.
DATESMTD:Returns a table that contains a column of dates for the month-to-date.
YEARFRAC:Returns the fraction of the year represented by the number of whole days between two dates.


LOGICAL FUNCTIONS:IF, SWITCH, AND, OR, NOT, TRUE, FALSE, ISEVEN, ISODD, IFERROR,IFNA

IF:Returns one value if a condition is true and another value if it's false.
SWITCH:Evaluates a series of conditions and returns the result of the first condition that is true.
AND:Returns TRUE if all the arguments are true, and FALSE otherwise.
OR:Returns TRUE if at least one of the arguments is true, and FALSE otherwise.
NOT:Returns the opposite of a logical value. If the argument is TRUE, NOT returns FALSE; if the argument is FALSE, NOT returns TRUE.
TRUE:Returns the logical value TRUE.
FALSE:Returns the logical value FALSE.
ISEVEN:Returns TRUE if the number is even, and FALSE if it's odd.
ISODD:Returns TRUE if the number is odd, and FALSE if it's even.
IFERROR:Returns a value you specify if a formula evaluates to an error; otherwise, it returns the result of the formula.
IFNA:Returns a value you specify if the expression is #N/A, otherwise returns the result of the expression.

OPERATORS 
arithmetic ( +, -, *, /), comparison (e.g., =, <>, >, <, >=, <=), logical (e.g., AND, OR, NOT), and concatenation (&) 

VISUALS:
Table:Displays data in a tabular format, allowing users to see detailed information.
Matrix:Similar to a table but provides a more flexible way to display summarized data.
Card:Represents a single value or KPI in a visually appealing way.
Chart Types:Various chart types are available, including:
Column Chart
Bar Chart
Line Chart
Area Chart
Pie Chart
Doughnut Chart
Scatter Chart
Bubble Chart
Treemap
Funnel Chart
Map:Displays data on a map, ideal for geospatial analysis.
Gauge:Represents a single value using a gauge or speedometer-style visualization.
KPI (Key Performance Indicator):Visualizes key metrics and performance indicators.
Card with States:A card that can change appearance based on predefined conditions.
Slicer:Allows users to filter data in other visuals by selecting values from a list.
Hierarchy Slicer:Extends the slicer functionality to support hierarchical data.
Drillthrough:Enables users to drill down into more detailed data.
Table and Matrix Drillthrough:Allows drilling into more detailed data in tables and matrices.
Q&A (Question and Answer):Allows users to ask natural language questions about the data.
R Script Visual:Integrates R scripts for advanced analytics and visualizations.
Custom Visuals:Users can import custom visuals created by the Power BI community or develop their own using the Power BI Developer tools.

DATA VISUALIZATIO  TECHNIQUES:
Histograms Area / Bar Charts Pie Charts
Pair-Plots ,Heatmaps, Fever Chart

MODIFYING COLORS IN CHARTS AND VISUALS
VISUALIZING DATA WITH MAPS
TREE MAP IN POWER Bl
BOOKMARKS AND BUTTONS,SHAPES IMAGES

BEST PRACTICE:
Create a separate table for measures
Limit Visuals: As visuals interact with each other, if we have more visuals, it might take a lot of time to refresh. Tool tips & Drill through can be used.
Process as much data as required in the original source
Certified Visuals are recommended
Use a lighter background

TOOL TIPS & DRILLTHROGHS:
EDIT INTERACTIONS:
FORMATTING OPTIONS:
ADMINISTRATIONS:
 admin, member, contributor, viewer

ADMINS:
Power BI Service Admins: Have full control over the Power BI service. They can manage capacities, configure settings, and control access.
Power BI Embedded Admins: Have permissions to configure and manage capacities in Power BI Embedded, an Azure service for embedding Power BI reports.

MEMBERS:
Members of Workspaces: Have the ability to view and interact with reports and dashboards within a workspace. They can also create and edit content within the workspace.
Members of Apps: Have permissions to access and consume content shared through apps. They can view and interact with app content.

CONTRIBUTORS:
Contributors to Workspaces: Have additional permissions beyond Members, allowing them to edit and modify the content in a workspace.

VIEWERS:
Viewers of Workspaces: Can view and interact with the content within a workspace but don't have permissions to edit or modify the content.

ADMIN:Admins can update and delete workspaces.
They can add or remove people, including other admins.
Admins have the ability to allow Contributors to update the app for the workspace.
They can publish, unpublish, and change permissions for an app.
Admins can update an app.
They can share items in apps, including semantic models.
Admins can allow others to reshare items.
They have the capability to feature apps on colleagues' home.
Admins can manage semantic model permissions.
They can feature dashboards and reports on colleagues' home.
Admins have full control, including creating, editing, and deleting content in the workspace.
They can publish reports to the workspace and delete content.
Admins can create a report in another workspace based on a semantic model in this workspace.
They can copy a report.
Admins have the ability to create metrics based on a semantic model in the workspace.
They can schedule data refreshes via the on-premises gateway.
Admins can modify gateway connection settings.
They can view and interact with any item.
Admins can read data stored in workspace dataflows.
They can create subscriptions to reports.
Admins can subscribe others to reports.
They can manage subscriptions created by others.
Admins can receive subscriptions created by others.

MEMBER:Members have the same capabilities as Admins, except for certain administrative tasks such as updating or deleting workspaces, managing admins, and modifying gateway connection settings.

CONTRIBUTOR:Contributors have the ability to add or remove people, including other contributors and viewers.
They can publish reports to the workspace and delete content.
Contributors can create a report in another workspace based on a semantic model in this workspace.
They can copy a report.
Contributors have the ability to create metrics based on a semantic model in the workspace.
They can schedule data refreshes via the on-premises gateway.
Contributors can modify gateway connection settings.
They can view and interact with any item.
Contributors can read data stored in workspace dataflows.
They can create subscriptions to reports.
Contributors can subscribe others to reports.
They can manage subscriptions created by others.
Contributors can receive subscriptions created by others.

VIEWER:Viewers have limited capabilities compared to Contributors.
They can view and interact with any item.
Viewers can read data stored in workspace dataflows.
They can create subscriptions to reports.
Viewers can subscribe others to reports.
They can manage subscriptions created by others.
Viewers can receive subscriptions created by others.









******

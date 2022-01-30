# DAU-Decrease-Event

**An SQL Project in Jupyter Notebook as the Frontend.** <br />
In order to produce **visualizations**, a combination of both Python and R was used

## Tableau Interactive Dashboard
[DAU Interactive Dashboard](https://public.tableau.com/views/DAUStatus/DAUStatus?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link)

<ins>The project includes the following steps:</ins>
1. *Establish a connection between jupyter and MSSQL:*
    1. Create a connection through an Open Database Connectivity (ODBC), Define an API for accessing the MSSQL database.
    1. Load the extensions required to run SQL queries in jupyter.
    1. Load the extensions required to run R syntax in jupyter.
1. *Data Validation:*
    1. Import data from the excel source file into jupyter.  
    1. Data investigation: Understanding its structure.
    1. Fix incompatiable data entries.
1. *Data Processing:*
    1. Create tables in the database for the data (A table, as the data is consists of 1 table).
    1. Load the validated data from jupyter to MSSQL.
1. *Data Manipulation, Analysis and Visualization:* <br />
    Define questions about the behavior of the product, reflected by the data.
           - Manipulate the data to produce the best data presentation form.
           - Create SQL View for Tableau application.
           - Visualize the data and answer the questions regarding the product. <br >
1. **Create a Dashboard with Tableau.**

<ins>SQL syntax and strategies that are used in the project:</ins>
1. Finding sequence of events using windowed Row_Number.
1. dynamic (DECLARE, SET, EXECUTE) PIVOT with FOR XML PATH.
1. multiple CTEs 
1. Recursive CTE and a FOR XML PATH Technique
1. Subqueries
1. Multiple inner joins inside a multiple CTEs and a Recursive CTE query
1. Casting and connecting date (dates, str)
1. Creating VIEWS


<ins>How Python is used in the project:</ins>
1. loading excel data file.
1. investing the data and converting incompatiable data entries with a def function
1. visualizations with seaborn.


<ins>How R is used in the project:</ins>
1. Visualizations with ggplot2

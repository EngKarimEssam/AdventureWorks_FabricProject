# AdventureWorks_FabricProject

Steps:
- Create Lakehouse, then load Excel file data.
- Load Data into Lakehouse using Dataflow Gen2.
  - Duplicate the file (Fact and Dims).
  - Check the data type and other transformations.
- Querying SQL using SQL analytics endpoint.
  - Same result can also be done using Visual Query, an easy and fast tool for complex queries to get it done faster than writing the code.
 
    
- Again, load the Excel (DimDate) file, but now magic comes, drag and drop the file into the table folder.
  - what we did inside a dataflow, the same process is happening in the background, taking that file and converting it to a parquet file and then creating the delta table (no complex😀).

- Use Power BI Desktop and connect to onelake, then create your star schema and the visualizations you need.
  - Tip: You can create a Power BI dataset for a group of people to see specific Data.
 
- In the lakehouse, we will get DimGeo using Data Pipeline
 



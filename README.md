Provide one word document that contains screenshots of your data model, database objects and row count of data loaded in each table. Note that this step is only to ensure that data has been loaded into the database. Use the attached document template to prepare your submission - complete "Data Model" and "Physical Database" sections of the report for this submission, along with group # and group members. Groups that do not complete this step will not be able to continue with the project. The due date is Nov 9, 11:59pm.

Design a database using good practices for database design and normalization. Use the data provided here. The business scenario is as follows.

Project Context

This data publication contains a spatial database of wildfires that occurred in the United States from 1992 to 2015. It is the third update of a publication originally generated to support the national Fire Program Analysis (FPA) system. The wildfire records were acquired from the reporting systems of federal, state, and local fire organizations. The following core data elements were required for records to be included in this data publication: discovery date, final fire size, and a point location at least as precise as Public Land Survey System (PLSS) section (1-square mile grid). The data were transformed to conform, when possible, to the data standards of the National Wildfire Coordinating Group (NWCG). Basic error-checking was performed and redundant records were identified and removed, to the degree possible. The resulting product, referred to as the Fire Program Analysis fire-occurrence database (FPA FOD), includes 1.88 million geo-referenced wildfire records, representing a total of 140 million acres burned during the 24-year period.

Content:
This dataset in sqlite format contains the following information:

Fires: Table including wildfire data for the period of 1992-2015 compiled from US federal, state, and local reporting systems.
NWCG_UnitIDActive_20170109: Look-up table containing all NWCG identifiers for agency units that were active (i.e., valid) as of 9 January 2017, when the list was downloaded from https://www.nifc.blm.gov/unit_id/Publish.html and used as the source of values available to populate the following fields in the Fires table: NWCG_REPORTING_AGENCY, NWCG_REPORTING_UNIT_ID, and NWCG_REPORTING_UNIT_NAME.

-----------------------------------------------------------------------------------------------------------------------------

Please write queries using mySQL and Mongo for 6 out of the 8 questions provided to you. Complete the appropriate sections in the project report you had started for the project that contains the data model. Please ensure that all sections in your document are completed, including previously submitted details for phase 1. Please ensure that you submit your response here in elearning before Sunday, 11:59pm, Dec 8 2019.  No exceptions will be allowed to this submission deadline.

A leading beverage company has announced a billion-dollar fund for removing debris from forests, rivers and mountains in the US. All states are interested. Which state has the best chance to win a share of the fund?
One of the reporting agencies has suggested that children be banned from its forests unless there is one adult for every 3 children in a group visiting a forest.Name 3 forests where this would be the most appropriate.
One advocacy group says Nature and not human actions is to blame for most wildfires. Write a query that supports this statement.
What are the top two unit types that reported wildfires in each county in the US? 
How many wildfires were reported by more than one unit/agency?
What were the forests that had more than one fire that lasted more than two days?
Which state had more fires in the second half of a calendar year than the first half of the calendar year?
Which forest had the most number of fires?
Provide screen shots containing your assumptions about the data, translation, query and results for each question below. Answer only 6 out of 8 questions. If all 8 are answered, ONLY the first 6 will be considered for grading. Provide your responses for both SQL and Mongo in the same document. You have two attempts to provide a response. Only the last response will be considered for grading. Do not email any submissions to this project - they will not be considered.



<h1 align="center">KickStart My Chart</h1>

Organize and analyze a database of four thousand past projects of kickstarter to uncover some hidden trends. 

## Reading guide for StarterBook.xlsx:

### Sheet1:
Each cell in the "state" column with a different color, depending on whether the associated campaign was "successful", 
"failed", "cancelled" or currently "live". Green represents "successful", red represents "failed", Yellow represents
"cancelled" and pink represents "live".

Cells in the "percent funded" column using a three-color scale. Red represents 0 to 99, Green represents 100-199,Blue 
represents greater than 199.

### Sheet "Outcome  by Parent Category":
A pivot table filtered by country, counts how many parent campaigns were "successful", "failed", "cancelled,"
currently "live", and percentage successful per parent category.
A bar chart is generated based on the pivot table.

### Sheet "Outcome by Sub-category":
A pivot table filtered by country and parent category, counts how many campaigns were "successful","failed",
"cancelled," or currently "live" per sub-category.
A bar chart is generated based on the pivot table.

###  Sheet "Outcome by Date Created":
A pivot table filtered by category and Years, counts how many campaigns were "successful", "failed", "cancelled" 
or currently "live" per month.
A line graph is generated based on the pivot table.

###  Sheet "Outcome by Goals":
Number Successful, Number Failed, and Number Canceled columns are calculated with COUNTIFS() regarding ranges.
A line chart which graphs the relationship between a goal's amount and its chances at success, failure, or cancellation.

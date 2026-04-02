#        My Journey In the Boycode 4.0 Data analysis Class

This portfolio showcases my data analysis Journey across three platforms, progressing from data cleaning and formula-based analysis in Excel spreadsheets to building interactive dashboards On PowerBi and querying relational databases on SQL.

### I would like to express my deepest gratitude to my tutor, Mr. Edu Ibrahim Olamilekan (a.k.a Drollazz).
Thank you for your patience, expert guidance, and for making the complex world of Data Analytics so accessible. This journey was made possible because of your dedication to our growth. I am truly grateful for the skills I've gained under your mentorship. 🙏❤️
## Scroll down read through and also use the drop down in the Table of content for breakdown


#        TABLE OF CONTENT

## EXCEL
## POWER BI

## SQL (Structured Query Language)
<details>
<summary><b>1. Database Environment & Administration "DROP,CREATE,..." (Beginner SQL)</b></summary>
<br>
  
- **Setup:** Dropping existing databases and creating fresh environments.
- **Schema Definition:** Creating tables with Primary Keys and Constraints.
- **Data Population:** Importing scripts and manual INSERT INTO statements.
</details>

<details>
<summary><b>2. Data Retrieval Fundamentals(SELECT,...) </b></summary>
<br>

- **Basic Selection:** Querying all columns vs. specific columns and DISTINCT values.
- **Arithmetic Operations:** Performing math directly within SELECT statements.
- **Aliasing:** Renaming columns and tables for clean, professional reporting.
</details>

<details>
<summary><b>3. Logical Filtering & Pattern Matching </b></summary>
<br>

- **Comparison Operators:** Using WHERE with `>`, `<`, and `!=`.
- **Logical Operators:** Combining multiple conditions with AND, OR, and NOT.
- **Wildcard Searching:** Advanced pattern matching using LIKE with `%` and `_`.
</details>

<details>
<summary><b>4. Data Aggregation & Sorting</b></summary>
<br>

- **Summarization:** Grouping data to find AVG, MAX, MIN, and COUNT.
- **Sorting Logic:** Ascending and Descending orders, including multi-level and positional sorting.
- **The HAVING Clause:** Filtering aggregated groups and understanding the order of execution.
</details>

<details>
<summary><b>5. Relational SQL (Joins & Unions) Intermediate SQL</b></summary>
<br>

- **Horizontal Joins:** INNER, LEFT, and RIGHT joins to connect multiple tables.
- **Advanced Joins:** SELF JOINS for internal row comparisons and multi-table linking.
- **Vertical Merging:** Using UNION and UNION ALL to stack data and create custom labels.
</details>

<details>
<summary><b>6. Intermediate Logic & String Function</b></summary>
<br>

- **Conditional Formatting:** Using CASE statements for tiered logic and bonuses.
- **String Cleaning:** TRIM, UPPER, LOWER, and REPLACE for data integrity.
- **Data Extraction:** Using SUBSTRING, CONCAT, and POSITION to parse text.
</details>

<details>
<summary><b>7. Advanced Analytical SQL (Advanced SQL)</b></summary>
<br>

- **Nested Logic:** Subqueries in the WHERE and FROM clauses.
- **Common Table Expressions (CTEs):** Creating modular, readable queries with WITH.
- **Window Functions:** Rolling totals, partitioning data, and ranking (Row Number, Rank, Dense Rank).
</details>

<details>
<summary><b>8. Procedural SQL & Session Management</b></summary>
<br>

- **Temporary Tables:** Creating session-based "sandboxes" for testing and data manipulation.
- **Stored Procedures:** Automating repetitive queries into reusable programs.
</details>

<details>
<summary><b>9. Data Cleaning</b></summary>
<br>

- **Remove Duplicates:** Identifying and deleting redundant records.
- **Standardizing:** Formatting data types and naming conventions.
- **Null values:** Handling blank spaces or NULL entries.
- **Remove empty columns:** Dropping unused fields.
</details>

## Objective 
The goal of this repository is to document my end-to-end data analytics journey, transitioning from raw data to actionable business insights under the guidance of my tutor, Mr Edu Ibrahim Olamilekan. I achieved this by mastering a three-pillar technical workflow:

Excel ➔ SQL  ➔ Power BI

## Tools & Techniques

| Tool | Application & Focus |
| :--- | :--- |
| **Excel** | Data cleaning, pivot tables, and creating interactive Dashboards. |
| **Power BI** | Advanced Data Modeling and majorly for high-level Visualization. |
| **SQL** | Database management, complex querying, and technical Data cleaning. |

## IMAGES AND BREIF EXPLANATION¬ 

## EXCEL:

### Number Formatting 
Number formatting is the actual outfit like design you put on a number in a cell it can be adding a it can be in form of converting the number from ordinary number to CURRENCY, PERCENTAGE, SPECIFIC TIME, DATE, e.t.c

STEPS:
-Click on the cell you wanr to edit 

-Under the home tab click on GENERAL 

-Chose the format of choioce
![](https://github.com/Ebenezer080925/Ogundaisi-Ebenezer---Boycode---4.0-Data-analysis-Cohort/blob/main/Number%20Formating.png)

### Counting Values with Count function
The COUNT function only counts cells that contain numbers. It ignores cells with text, icons, or empty spaces 
![](https://github.com/Ebenezer080925/Ogundaisi-Ebenezer---Boycode---4.0-Data-analysis-Cohort/blob/main/Counting%20Value%20with%20the%20COUNT%20function%20.png)

### Calculating with sum function
SUMIF is a function that adds the values in a range that meet a single criteria you specify.
![](https://github.com/Ebenezer080925/Ogundaisi-Ebenezer---Boycode---4.0-Data-analysis-Cohort/blob/main/Calculating%20with%20the%20sum%20function.png)

### Format Painting
Format Painter (in Excel, Word, etc.) is a tool that lets you copy the appearance of something and apply it to something else.
![](https://github.com/Ebenezer080925/Ogundaisi-Ebenezer---Boycode---4.0-Data-analysis-Cohort/blob/main/Format%20painter.png)

### Formulas and function
There are some major formulas which are ADDITION"+", SUBTRACTION"-", MULTIPLICATION"*", DIVISION"/",...... for the calculations that are require multiple formulas so you follow a specific arrangment when calculating BODMAS(Bracket, Of, Division Multiplication, Addition, Subtraction) and PIDMAS(parenthesis,Indceis,Division, Multiplication, Addition, Subtraction)
![](https://github.com/Ebenezer080925/Ogundaisi-Ebenezer---Boycode---4.0-Data-analysis-Cohort/blob/main/formulas%20and%20function.png)

### Using Min and Max
The Max and Min is use for checking the maximum and minimum value in a column 
![](https://github.com/Ebenezer080925/Ogundaisi-Ebenezer---Boycode---4.0-Data-analysis-Cohort/blob/main/Using%20MIN%20and%20MAX.png)

### Date and time formatting
Date and time formatting is a way of representing your Date and time in the way you like. e.g Date, long date, short date, e.t.c
![](https://github.com/Ebenezer080925/Ogundaisi-Ebenezer---Boycode---4.0-Data-analysis-Cohort/blob/main/Date%20and%20time%20format.png)

### Using Name Ranges in Calculation 
Name Ranges are descriptive name assigned to a cell or a range of cells.
Instead of writing =SUM(E4:E17), you name that range "Runtimes" and write =SUM(Total)
![](https://github.com/Ebenezer080925/Ogundaisi-Ebenezer---Boycode---4.0-Data-analysis-Cohort/blob/main/Using%20Name%20Ranges%20in%20Calculation%202.png)

### Flash fill
Flash Fill is like a "mind-reading" tool in Excel and Google Sheets. It is a special feature that senses patterns in your data and automatically fills in the rest of the column for you.
![](https://github.com/Ebenezer080925/Ogundaisi-Ebenezer---Boycode---4.0-Data-analysis-Cohort/blob/main/Flash%20Fill.png)

### Error Handling
Error Handling is the process of anticipating, detecting, and resolving mistakes in your formulas
When a formula can't calculate correctly, Excel or Google Sheets will throw an "Error Code" (like #VALUE! or #N/A). Error handling helps you replace those ugly codes with friendly messages or alternative calculations
![](https://github.com/Ebenezer080925/Ogundaisi-Ebenezer---Boycode---4.0-Data-analysis-Cohort/blob/main/Error%20Handling.png)

### CELL STYLE 
A "Cell Style" is a predefined set of formatting characteristics—such as fonts, font sizes, number formats, cell borders, and cell shading—that you can apply to a cell all at once.
![](https://github.com/Ebenezer080925/Ogundaisi-Ebenezer---Boycode---4.0-Data-analysis-Cohort/blob/main/Cell%20style%202.png)

### CONTROL DATA INPUT 

![](https://github.com/Ebenezer080925/Ogundaisi-Ebenezer---Boycode---4.0-Data-analysis-Cohort/blob/main/Countrol%20Data%20Input%20Assignment.png)

### BASIC LOGICAL FUNCTION 
Basic Logi function are functions that allows us to ask a comparision question that give us the response TRUE/FALSE or what we want 

=IF(B5>$G$5,True,False)
![](https://github.com/Ebenezer080925/Ogundaisi-Ebenezer---Boycode---4.0-Data-analysis-Cohort/blob/main/Basic%20Logical%20function%20Assignment.png)

### LOGICAL FUNCTION 
logical functions are the "decision-makers" of a spreadsheet or programming language. They evaluate a situation and return a result—usually TRUE or FALSE—based on whether a specific condition is met.

-IF-Function:	Checks if a condition is met and returns one value if true, another if false. e.g =IF(B4>=85, "Pass", "Fail")

-And-FUNCTION: Returns TRUE only if all conditions provided are true.  =IF(AND(C23>=65, B23>=75), "Pass", "Fail")

-OR-FUNCTION: Returns TRUE if at least one of the conditions is true. =IF(OR(B33>=75, C33>=65), "Pass", "Fail")

-NOT-FUNCTION: Reverses the logic (turns TRUE into FALSE and vice versa). 
![](https://github.com/Ebenezer080925/Ogundaisi-Ebenezer---Boycode---4.0-Data-analysis-Cohort/blob/main/Logical%20function%20Assignment.png)

### IF FUNCTIONS 
IF function is a logical tool that tells your spreadsheet: "Check if this condition is met. If it is, do one thing; if it isn't, do something else.

=IF(F4>$K$3,$K$4*F4,"-") Shipping column

=IF(F4>$K$3,($K$4*F4)+F4,F4) Total column
![](https://github.com/Ebenezer080925/Ogundaisi-Ebenezer---Boycode---4.0-Data-analysis-Cohort/blob/main/if%20function%20assignment.png)

### NESTED IF ASSIGNMENT 
A Nested IF is simply an IF function placed inside another IF function.Also does the work of IFS 

=IF(G2=$J$4, $K$4, IF(G2=$J$5, $K$5, IF(G2=$J$6, $K$6, IF(G2=$J$7, $K$7, IF(G2=$J$8, "0", "No bonus")))))
![](https://github.com/Ebenezer080925/Ogundaisi-Ebenezer---Boycode---4.0-Data-analysis-Cohort/blob/main/Nested%20if%20assignment.png)

### COUNTIF(S) and SUMIF(S) Assignment 
COUNTIF(S):Counts how many times a value appears in a list, but only if it meets one or more specific conditions.
=COUNTIFS(Criteria_Range1, "Condition1", Criteria_Range2, "Condition2", ...)

SUMIF(S): Adds up numbers in a range, but only if they meet one or more specific conditions.
=SUMIFS(Range_to_Add, Criteria_Range1, "Condition1", ...)

![](https://github.com/Ebenezer080925/Ogundaisi-Ebenezer---Boycode---4.0-Data-analysis-Cohort/blob/main/COUNTIF(S)%20and%20SUMIF(S)%20Assignment.png)

### Data for the VLOOKUP
VLOOKUP stands for Vertical Lookup. It is a tool that tells your spreadsheet: "Go find this specific piece of information in the first column of a table, and then tell me what is in the same row but a different column.

- =VLOOKUP(lookup_value, table_array, col_index_num, [range_lookup]), For the range lookup FALSE meant it must be the exact value the TRUE mean approximate
![](https://github.com/Ebenezer080925/Ogundaisi-Ebenezer---Boycode---4.0-Data-analysis-Cohort/blob/main/VLOOKUP%20Data.png)

### VLOOKUP-exact-match Description
=VLOOKUP(A5, 'Parts Catalogue'!$A$3:$C$87, 2, FALSE)
![](https://github.com/Ebenezer080925/Ogundaisi-Ebenezer---Boycode---4.0-Data-analysis-Cohort/blob/main/VLOOKUP-exact-match%20Description.png)

### VLOOKUP-exact-match Unit price
=VLOOKUP(A5, 'Parts Catalogue'!$A$3:$C$87, 3, FALSE)
![](https://github.com/Ebenezer080925/Ogundaisi-Ebenezer---Boycode---4.0-Data-analysis-Cohort/blob/main/VLOOKUP-exact-match%20Unit%20Price.png)


### Using-Index-match
INDEX-MATCH is a combination of two separate Excel functions used together to perform a more flexible and powerful lookup than the traditional VLOOKUP.
syntax =INDEX(\text{column\_to\_return}, MATCH(\text{lookup\_value}, \text{column\_to\_search}, 0))
![](https://github.com/Ebenezer080925/Ogundaisi-Ebenezer---Boycode---4.0-Data-analysis-Cohort/blob/main/Using-Index%20-match.png)

### Sorting on multiple Column BEFORE SORT
Sorting on multiple columns (often called multi-level sorting) is a method of organizing data hierarchically using two or more criteria. It involves arranging a dataset by a primary attribute first, and then using one or more secondary attributes as "tie-breakers" to determine the final order of items that share the exact same primary value.
![](https://github.com/Ebenezer080925/Ogundaisi-Ebenezer---Boycode---4.0-Data-analysis-Cohort/blob/main/Sorting%20on%20multiple%20column%20BF.png)

### Sorting on multiple Column AFTER SORT 
=SORT(range, sort_column1, is_ascending1, [sort_column2, is_ascending2, ...])

=SORT(A4:I18,G4:G18,TRUE,C4:C18,TRUE) the TRUE tells the sheet to sort them in Ascending other 
![](https://github.com/Ebenezer080925/Ogundaisi-Ebenezer---Boycode---4.0-Data-analysis-Cohort/blob/main/Sorting%20on%20multiple%20column%20AF.png)

### Sorting Using a Custom List BEFORE SORT
Sorting using a custom list means organizing your data based on your own specific, predefined order, rather than using the standard alphabetical (A to Z) or numerical (1 to 10) rules.
![](https://github.com/Ebenezer080925/Ogundaisi-Ebenezer---Boycode---4.0-Data-analysis-Cohort/blob/main/Sorting%20using%20a%20custom%20list%20BF.png)

### Sorting Using a custom List AFTER SORT 
=SORT(Data_Range, MATCH(Column_to_Sort, {"First", "Second", "Third"}, 0), TRUE)

=SORT(A4:I18, MATCH(A4:A18, {"Mr", "Mrs", "Miss"}, 0), TRUE)

{"Mr", "Mrs", "Miss"}: This is your custom rulebook. The formula assigns a hidden "1" to every Mr, a "2" to every Mrs, and a "3" to every Miss.

0: This simply forces the formula to look for exact word matches.
![](https://github.com/Ebenezer080925/Ogundaisi-Ebenezer---Boycode---4.0-Data-analysis-Cohort/blob/main/sorting%20using%20a%20column%20list%20AF.png)

### Sorting Using the SORT Function BEFORE SORT
The SORT function is a formula that takes a messy block of data and automatically creates a neatly organized, sorted copy of it in a new location.
![](https://github.com/Ebenezer080925/Ogundaisi-Ebenezer---Boycode---4.0-Data-analysis-Cohort/blob/main/Sorting%20Using%20the%20SORT%20Function%20BF.png)

### Sorting Using the SORT Function AFTER SORT
=SORT(range, sort_column, is_ascending)

=SORT(A5:D29, 4, FALSE) Sorting by Mark

=SORT(A5:D29, 3, TRUE, 4, FALSE) Sort by Exam Subject, then by Highest Mark
![](https://github.com/Ebenezer080925/Ogundaisi-Ebenezer---Boycode---4.0-Data-analysis-Cohort/blob/main/Sorting%20Using%20the%20SORT%20Function%20AF.png)

### Extracting a Unique List using Unique Function
The UNIQUE function is a tool that looks through a list of data, automatically removes any duplicate entries, and gives you back a clean list where every item appears exactly once.
We also use the sort function with the Unique
![](https://github.com/Ebenezer080925/Ogundaisi-Ebenezer---Boycode---4.0-Data-analysis-Cohort/blob/main/Extract%20Unique%20Values%20using%20the%20UNIQUE%20Function.png)

### Filtering Using the FILTER Function
A formula that looks at the master list and extracts only the rows that match one specific rule, giving you a clean mini-list. ( pulling only the "English" students).

=FILTER(Range, Rule)

=FILTER(A5:D29, C5:C29=F5)
![](https://github.com/Ebenezer080925/Ogundaisi-Ebenezer---Boycode---4.0-Data-analysis-Cohort/blob/main/Filtering%20Using%20the%20FILTERTING%20Function.png)

### Filtering Multiple Criteria 
Using the same FILTER function but giving it two or more rules separated by commas. The formula will only extract a row if it meets all the rules at the exact same time. ( finding students who take "English" AND are in the "West" block).

=FILTER(Range, Rule1, Rule2)

=FILTER(A5:D29, C5:C29=F5, A5:A29=F8)
![](https://github.com/Ebenezer080925/Ogundaisi-Ebenezer---Boycode---4.0-Data-analysis-Cohort/blob/main/Filtering%20Multiple%20Criteria.png)

### Filtering Filter and Sorting
The inside FILTER does the first job of extracting the specific data you asked for. Then, the outside SORT does the second job of arranging that newly extracted list into a logical order, like highest to lowest. (finding the English/West/>50 students, and ordering them by who got the best grade).

=SORT(FILTER(Range, Rule1, Rule2), Sort_Column_Number, TRUE/FALSE)

=SORT(FILTER(A5:D29, C5:C29=F5, A5:A29=F8, D5:D29>50), 4, FALSE)
![](https://github.com/Ebenezer080925/Ogundaisi-Ebenezer---Boycode---4.0-Data-analysis-Cohort/blob/main/Filtering%20FILTER%20and%20SORT.png)

### How Dates and Times are stored in Excel
a DateTime Serial Number is a continuous, floating-point numeric scale used to represent both dates and times. Instead of storing complex calendar data (like "January" or "Tuesday"), the computer stores a single numeric value where the integers represent whole days passed since a foundational starting point, and the decimal fractions represent the precise time elapsed within the current day.

0.0 = 12:00 AM (Midnight, the very start of the day)

0.25 = 6:00 AM (25% of the day is over)

0.5 = 12:00 PM (Noon, exactly 50% or half the day)

0.75 = 6:00 PM (75% of the day is over)
Steps: Highlight the column you want to adjust - Look at the Home ribbon - Go to General - Then select the date format - Long OR Short 
![]()

### Date Functions
Date Functions are formulas that allow you to take a complete date and slice it into individual pieces (like extracting just the year or the day), OR take scattered numbers and glue them back together into a single, functional spreadsheet date.

![]()

### Time Functions
Time Extraction Functions (HOUR, MINUTE, SECOND) They allow you to pull out just one specific piece of that time—either the hour, the minute, or the second—and display it as a plain, standalone number.
=HOUR()

=MINUTE()

=SECOND()
![]()


# ------------------------------------------------------------------------------

## POWER BI:
### HR DASHBOARD 
![](https://github.com/Ebenezer080925/Ogundaisi-Ebenezer---Boycode---4.0-Data-analysis-Cohort/blob/main/HR%20Dashboard.jpg)

# ------------------------------------------------------------------------------

## SQL(Postgre)

## 1. Database Environment & Administration (Beginner SQL)

## Importing SQL Queries:
### Demonstrating the process of importing and executing external SQL scripts to build out entire database schemas efficiently.
![](https://github.com/Ebenezer080925/Ogundaisi-Ebenezer---Boycode---4.0-Data-analysis-Cohort/blob/main/importing%20SQL%20queries.png)

## Drop Create and use
### Setting up the environment by ensuring a clean slate—dropping any existing database version before creating and selecting the Parks_and_Recreation database for use.
![](https://github.com/Ebenezer080925/Ogundaisi-Ebenezer---Boycode---4.0-Data-analysis-Cohort/blob/main/Drop%2C%20Create%20and%20USE.png)

## Creating a table
### Defining the structural blueprint of the project, including data types, NOT NULL constraints, and setting Primary Keys for the demographics and salary tables
![](https://github.com/Ebenezer080925/Ogundaisi-Ebenezer---Boycode---4.0-Data-analysis-Cohort/blob/main/Creating%20a%20table.png)

## Inserting values into a table 
### Populating the tables with project data using the INSERT INTO statement, ensuring each record aligns with the defined schema.
![](https://github.com/Ebenezer080925/Ogundaisi-Ebenezer---Boycode---4.0-Data-analysis-Cohort/blob/main/Inserting%20into%20value.png)

## 2. Data Retrieval Fundamentals

## Selecting the employee salaries table
### Mastering the basic SELECT * statement to retrieve all records and columns from the employee_salary table
![](https://github.com/Ebenezer080925/Ogundaisi-Ebenezer---Boycode---4.0-Data-analysis-Cohort/blob/main/Select%20employee%20salary.png)

## Selecting the employee demograhics table
### Mastering the basic SELECT * statement to retrieve all records and columns from the employee_salary table
![](https://github.com/Ebenezer080925/Ogundaisi-Ebenezer---Boycode---4.0-Data-analysis-Cohort/blob/main/Select%20%20employee%20demographics.png)

## Selecting multiple column
### Learning to be selective with data by specifying only the columns needed (employee_id, first_name, etc.), which optimizes query performance.
![](https://github.com/Ebenezer080925/Ogundaisi-Ebenezer---Boycode---4.0-Data-analysis-Cohort/blob/main/select%20multiple%20Column.png)

## Selecting multiple column in a straight line 
### Querying multiple specific columns simultaneously to view related data points, such as linking employee names with their specific job titles.
![](https://github.com/Ebenezer080925/Ogundaisi-Ebenezer---Boycode---4.0-Data-analysis-Cohort/blob/main/Selecting%20multiple%20column%20straight.png)

## Selecting specified column first_name
### Demonstrating how to retrieve a single, targeted column from a table to maintain a clean and focused output.
![](https://github.com/Ebenezer080925/Ogundaisi-Ebenezer---Boycode---4.0-Data-analysis-Cohort/blob/main/Select%20specific%20column%20%20First%20name%20.png)

## Select base on highlighted value
### Demonstrating a professional workflow by highlighting and executing a specific query within a larger script to isolate a single result set.
![](https://github.com/Ebenezer080925/Ogundaisi-Ebenezer---Boycode---4.0-Data-analysis-Cohort/blob/main/Select%20Base%20on%20highlight.png)

## Select Distint value
### Using the DISTINCT keyword to identify unique values within a column, effectively removing duplicates from the results.
![](https://github.com/Ebenezer080925/Ogundaisi-Ebenezer---Boycode---4.0-Data-analysis-Cohort/blob/main/Select%20Distinct%20.png)

## Quick cal. adding to age while selecting
### Performing dynamic arithmetic directly within a SELECT statement to create calculated columns (e.g., projecting ages 10 years into the future).
![](https://github.com/Ebenezer080925/Ogundaisi-Ebenezer---Boycode---4.0-Data-analysis-Cohort/blob/main/Quick%20cal.%20adding%20to%20age%20while%20selecting.png)

### Select multiple rows with calculations order
![](https://github.com/Ebenezer080925/Ogundaisi-Ebenezer---Boycode---4.0-Data-analysis-Cohort/blob/main/Select%20multiple%20row%20with%20calculatios%20in%20orders.png)

## 3. Logical Filtering & Pattern Matching
## Using where clause
### Isolating a specific record by matching a string value—in this case, retrieving all available data for 'Leslie'.
![](https://github.com/Ebenezer080925/Ogundaisi-Ebenezer---Boycode---4.0-Data-analysis-Cohort/blob/main/Using%20where%20clause.png)

## greater where clause
### Using comparison operators to filter salary data, specifically isolating all employees earning strictly above 50,000
![](https://github.com/Ebenezer080925/Ogundaisi-Ebenezer---Boycode---4.0-Data-analysis-Cohort/blob/main/greater%20where%20clause%20.png)

## Greater than equal to where clause
### Expanding search results to include boundary values by filtering for salaries that are at least 50,000 or more.
![](https://github.com/Ebenezer080925/Ogundaisi-Ebenezer---Boycode---4.0-Data-analysis-Cohort/blob/main/Greater%20than%20equal%20to%20where%20clause%20.png)

## Less than where clause 
### Identifying specific budget segments by filtering for records where the salary falls below the 50,000 threshold.
![](https://github.com/Ebenezer080925/Ogundaisi-Ebenezer---Boycode---4.0-Data-analysis-Cohort/blob/main/Less%20than%20where%20clause.png)

## Not equal to where clause
### Exploring exclusion logic using the != operator to filter out specific groups, such as excluding 'Female' records to isolate specific demographic segments.
![](https://github.com/Ebenezer080925/Ogundaisi-Ebenezer---Boycode---4.0-Data-analysis-Cohort/blob/main/Not%20equal%20to%20where%20clause%20.png)

## Greater than specific date where clause 
### Filtering time-series data to identify employees born after a specific date ('1985-01-01')—useful for age-based demographic analysis
![](https://github.com/Ebenezer080925/Ogundaisi-Ebenezer---Boycode---4.0-Data-analysis-Cohort/blob/main/greater%20than%20specific%20date%20where%20clause.png)

## Where clause and logical operators AND
### Combining multiple filters using AND. This ensures the results only include records that meet all conditions (e.g., born after 1985 and identified as Male).
![](https://github.com/Ebenezer080925/Ogundaisi-Ebenezer---Boycode---4.0-Data-analysis-Cohort/blob/main/where%20clause%20and%20logical%20operators%20AND.png)

## Where clause and logical operators OR
### Widening search results with OR. This retrieves records that satisfy either of the specified conditions, effectively increasing the dataset's scope.
![](https://github.com/Ebenezer080925/Ogundaisi-Ebenezer---Boycode---4.0-Data-analysis-Cohort/blob/main/where%20clause%20and%20logical%20operators%20OR.png)

## Where clause and logical operators OR and NOT
### Implementing advanced logic using NOT. This demonstrates how to retrieve records born after a certain date while explicitly excluding a specific group (e.g., excluding 'Male' records) within the same query.
![](https://github.com/Ebenezer080925/Ogundaisi-Ebenezer---Boycode---4.0-Data-analysis-Cohort/blob/main/where%20clause%20and%20logical%20operators%20OR%20and%20NOT.png)

## Like with Percentage %
### Using the % wildcard to filter for records where a name begins with specific characters, such as 'Jer'.
![](https://github.com/Ebenezer080925/Ogundaisi-Ebenezer---Boycode---4.0-Data-analysis-Cohort/blob/main/Like%20with%20percentage%20.png)

## Like with percentage from the middle words 
### Mastering flexible searching using the % wildcard to find records where a specific string (like 'er') appears anywhere within a name.
![](https://github.com/Ebenezer080925/Ogundaisi-Ebenezer---Boycode---4.0-Data-analysis-Cohort/blob/main/Like%20and%20percentage%20in%20for%20middle%20words.png)

## Like and underscore with numbers of character 2
### Deepening my use of the underscore (_) wildcard to match exactly two characters following a specific letter, allowing for high-precision pattern filtering.
![](https://github.com/Ebenezer080925/Ogundaisi-Ebenezer---Boycode---4.0-Data-analysis-Cohort/blob/main/Like%20and%20underscore%20with%20numbers%20of%20characters%202.png)

## Like and underscore with numbers of character 3
### Deepening my use of the underscore (_) wildcard to match exactly three characters following a specific letter, allowing for high-precision pattern filtering.
![](https://github.com/Ebenezer080925/Ogundaisi-Ebenezer---Boycode---4.0-Data-analysis-Cohort/blob/main/Like%20and%20underscore%20with%20numbers%20of%20characters%203.png)

## Like and underscore with numbers of Characters and any letter else
### Using the underscore (_) wildcard for precision pattern matching, ensuring a search results in names starting with 'A' followed by a specific number of characters.
![](https://github.com/Ebenezer080925/Ogundaisi-Ebenezer---Boycode---4.0-Data-analysis-Cohort/blob/main/Like%20and%20underscore%20with%20numbers%20of%20characters%20%20and%20any%20letter%20else.png)

## 4. Data Aggregation & Sorting

## Group by
### Learning to consolidate data into unique categories (e.g., by gender) to prepare for statistical analysis.
![](https://github.com/Ebenezer080925/Ogundaisi-Ebenezer---Boycode---4.0-Data-analysis-Cohort/blob/main/Group%20by.png)

## Group by with AVG
### Using the AVG() function alongside GROUP BY to calculate the mean age for different demographics.
![](https://github.com/Ebenezer080925/Ogundaisi-Ebenezer---Boycode---4.0-Data-analysis-Cohort/blob/main/Group%20by%20with%20AVG.png)

## Group by with multiple column
### Deepening analysis by grouping by multiple dimensions (e.g., Occupation and Salary) to see unique combinations of data.
![](https://github.com/Ebenezer080925/Ogundaisi-Ebenezer---Boycode---4.0-Data-analysis-Cohort/blob/main/Group%20by%20with%20multiple%20column.png)

## Group by with Aggregrate function
### Performing comprehensive statistical summaries in a single query by calculating the Average, Maximum, Minimum, and Total Count for each group.
![](https://github.com/Ebenezer080925/Ogundaisi-Ebenezer---Boycode---4.0-Data-analysis-Cohort/blob/main/Group%20by%20with%20Aggregate%20functions.png)

## Order by ASC
### Organizing output in ascending order (ASC)—alphabetizing names from A to Z for structured reporting.
![](https://github.com/Ebenezer080925/Ogundaisi-Ebenezer---Boycode---4.0-Data-analysis-Cohort/blob/main/Order%20by%20ASC.png)

## Order by DESC
### Reversing the sort order (DESC) to prioritize the most recent or highest values in a dataset.
![](https://github.com/Ebenezer080925/Ogundaisi-Ebenezer---Boycode---4.0-Data-analysis-Cohort/blob/main/Order%20by%20DESC.png)

## Order by with arrangement of the gender by male age and female 
### Implementing multi-level sorting—first by gender, then by age—to create a hierarchical view of the data.
![](https://github.com/Ebenezer080925/Ogundaisi-Ebenezer---Boycode---4.0-Data-analysis-Cohort/blob/main/Order%20by%20with%20arrangement%20of%20the%20gender%20by%20male%20age%20and%20female.png)

## Order by not Unique column
### Exploring the limitations of sorting; highlighting how ordering by non-unique columns can lead to 'useless' or inconsistent arrangements without a secondary sort key.
![](https://github.com/Ebenezer080925/Ogundaisi-Ebenezer---Boycode---4.0-Data-analysis-Cohort/blob/main/Order%20by%20not%20Unique%20column.png)

## Order by column number not name
### A professional shorthand technique—sorting data using column positions (e.g., Order by 5, 4) instead of typing out long column names.
![](https://github.com/Ebenezer080925/Ogundaisi-Ebenezer---Boycode---4.0-Data-analysis-Cohort/blob/main/Order%20by%20column%20number%20not%20name.png)

## HAVING VS WHERE not correct
### Demonstrating the correct use of HAVING to filter groups based on aggregate values (like an average age > 40), which cannot be done with a standard WHERE clause.
![](https://github.com/Ebenezer080925/Ogundaisi-Ebenezer---Boycode---4.0-Data-analysis-Cohort/blob/main/Having%20VS%20Where%20NOT%20correct.png)

## HAVING VS WHERE correct
### Demonstrating the correct use of HAVING to filter groups based on aggregate values (like an average age > 40), which cannot be done with a standard WHERE clause.
![](https://github.com/Ebenezer080925/Ogundaisi-Ebenezer---Boycode---4.0-Data-analysis-Cohort/blob/main/Having%20VS%20Where%20correct.png)

## HAVING VS WHERE and group by proper arrangement 
### Mastering query structure. This image shows the logical flow of a query: filtering raw rows with WHERE, grouping them, and then filtering those groups with HAVING
![](https://github.com/Ebenezer080925/Ogundaisi-Ebenezer---Boycode---4.0-Data-analysis-Cohort/blob/main/Having%20VS%20Where%20and%20Group%20by%20proper%20arrangement%20.png)

## LIMIT
### Controlling the volume of data returned. This is essential for testing queries on large datasets without overwhelming the system.
![](https://github.com/Ebenezer080925/Ogundaisi-Ebenezer---Boycode---4.0-Data-analysis-Cohort/blob/main/LIMIT.png)

## LIMIT Top 3
### Controlling the volume of data returned. This is essential for testing queries on large datasets without overwhelming the system.
![](https://github.com/Ebenezer080925/Ogundaisi-Ebenezer---Boycode---4.0-Data-analysis-Cohort/blob/main/LIMIT%20Top%203.png)

## ALIASING 
### Using the AS keyword to rename aggregated columns (like avg_age), making the final output intuitive and professional for end-users.
![](https://github.com/Ebenezer080925/Ogundaisi-Ebenezer---Boycode---4.0-Data-analysis-Cohort/blob/main/Aliasing.png)

## 5. Relational SQL (Joins & Unions) Intermediate SQL

## JOIN
### The core of relational databases—using an INNER JOIN to combine the demographics and salary tables based on a shared employee_id.
![](https://github.com/Ebenezer080925/Ogundaisi-Ebenezer---Boycode---4.0-Data-analysis-Cohort/blob/main/JOIN.png)

##  JOIN with Aliasing
### Combining advanced techniques. Using table aliases (like dem and sal) to write shorter, more efficient join queries while avoiding column name ambiguity.
![](https://github.com/Ebenezer080925/Ogundaisi-Ebenezer---Boycode---4.0-Data-analysis-Cohort/blob/main/JOIN%20With%20Aliasing%20.png)

## JOIN getting a specific column
### Refining joined data to extract exactly what is needed—such as matching an employee's ID and age from one table with their occupation from another.
![](https://github.com/Ebenezer080925/Ogundaisi-Ebenezer---Boycode---4.0-Data-analysis-Cohort/blob/main/JOIN%20getting%20specific%20column.png)

## LEFT JOIN
### Implementing a LEFT JOIN to ensure all records from the 'left' table (demographics) are preserved, even if there is no matching record in the salary table.
![](https://github.com/Ebenezer080925/Ogundaisi-Ebenezer---Boycode---4.0-Data-analysis-Cohort/blob/main/JOIN%20.LEFT%20JOIN.png)

## RIGHT JOIN 
### Using a RIGHT JOIN to prioritize the salary table, showcasing how NULL values appear when an employee has a salary record but missing demographic details.
![](https://github.com/Ebenezer080925/Ogundaisi-Ebenezer---Boycode---4.0-Data-analysis-Cohort/blob/main/JOIN%20.RIGHT%20JOIN%20.png)

## SELF JOIN
### Mastering the SELF JOIN technique to compare rows within the same table—a powerful method for finding internal relationships or hierarchical data.
![](https://github.com/Ebenezer080925/Ogundaisi-Ebenezer---Boycode---4.0-Data-analysis-Cohort/blob/main/JOIN%20.SELF%20JOIN.png)

## SELF JOIN by solving Assignng of task
### A creative use case for SELF JOIN: using a primary key offset (id + 1) to logically link employees together, such as for a 'Secret Santa' or peer-review assignment.
![](https://github.com/Ebenezer080925/Ogundaisi-Ebenezer---Boycode---4.0-Data-analysis-Cohort/blob/main/JOIN%20.SELF%20JOIN%20Assigning%20task.png)

## Join multiple table 
### Demonstrating the ability to link three or more tables simultaneously (Demographics, Salary, and Departments) to create a comprehensive view of the organizational structure.
![](https://github.com/Ebenezer080925/Ogundaisi-Ebenezer---Boycode---4.0-Data-analysis-Cohort/blob/main/JOIN%20multiple%20table%20.png)

## UNION
### Merging results from two different tables vertically. Using UNION automatically removes duplicates to provide a list of unique names across the entire organization.
![](https://github.com/Ebenezer080925/Ogundaisi-Ebenezer---Boycode---4.0-Data-analysis-Cohort/blob/main/UNION%20.png)

## UNION ALL
### Using UNION ALL to stack data while preserving every single record, providing a complete count of all entries without filtering for uniqueness.
![](https://github.com/Ebenezer080925/Ogundaisi-Ebenezer---Boycode---4.0-Data-analysis-Cohort/blob/main/UNION%20ALL%20.png)

## UNION use case 
### Applying professional data labeling within a UNION. By adding custom string columns (like 'Highly Paid Employee' or 'old'), I transformed raw filtered results into a meaningful categorical report.
![](https://github.com/Ebenezer080925/Ogundaisi-Ebenezer---Boycode---4.0-Data-analysis-Cohort/blob/main/UNION%20use%20case%20.png)

### UNION case 2
![](https://github.com/Ebenezer080925/Ogundaisi-Ebenezer---Boycode---4.0-Data-analysis-Cohort/blob/main/UNION%20use%20case%202.png)

## 6. Intermediate Logic & String Function

### String function with Length 
![](https://github.com/Ebenezer080925/Ogundaisi-Ebenezer---Boycode---4.0-Data-analysis-Cohort/blob/main/String%20function%20with%20Length.png)

## String function with Length, order by
### Measuring string depth and using the LENGTH() function as a sorting key—useful for identifying abnormally short or long entries (like IDs or phone numbers).
![](https://github.com/Ebenezer080925/Ogundaisi-Ebenezer---Boycode---4.0-Data-analysis-Cohort/blob/main/String%20function%20with%20Length%2C%20order%20by.png)

## String function with Upper & Lower
### Standardizing text case across a dataset to ensure uniformity, which is critical for professional presentation and case-sensitive data environments.
![](https://github.com/Ebenezer080925/Ogundaisi-Ebenezer---Boycode---4.0-Data-analysis-Cohort/blob/main/String%20function%20with%20Upper%26Lower.png)

## TRIM
### Data cleaning essentials—using TRIM to remove all surrounding whitespace
![](https://github.com/Ebenezer080925/Ogundaisi-Ebenezer---Boycode---4.0-Data-analysis-Cohort/blob/main/TRIM.png)

## LTRIM
### LTRIM to specifically clear leading spaces, ensuring data integrity for joins and searches.
![](https://github.com/Ebenezer080925/Ogundaisi-Ebenezer---Boycode---4.0-Data-analysis-Cohort/blob/main/TRIM%2C%20LTRIM.png)

## String function with SUBSTRING
### Slicing strings to extract specific segments—such as pulling out the first 4 characters or a middle section—to isolate relevant identifiers.
![](https://github.com/Ebenezer080925/Ogundaisi-Ebenezer---Boycode---4.0-Data-analysis-Cohort/blob/main/String%20function%20with%20SUBSTRING%20.png)

## String function with EXTRACT
### Bridging the gap between dates and numbers. Using EXTRACT to pull specific components like the Month or Year from a timestamp to perform seasonal or time-based grouping.
![](https://github.com/Ebenezer080925/Ogundaisi-Ebenezer---Boycode---4.0-Data-analysis-Cohort/blob/main/String%20function%20with%20EXTRACT.png)

## String function with Replace
### Executing bulk updates by replacing specific characters or patterns (e.g., swapping 'A' for 'Z') within a column without affecting the rest of the string.
![](https://github.com/Ebenezer080925/Ogundaisi-Ebenezer---Boycode---4.0-Data-analysis-Cohort/blob/main/String%20function%20with%20Replace.png)

## String function with POSITION in place of LOCATE 
### Locating the exact index of a character or substring. This provides a dynamic way to parse complex text based on where specific markers (like '@' or '-') occur.
![](https://github.com/Ebenezer080925/Ogundaisi-Ebenezer---Boycode---4.0-Data-analysis-Cohort/blob/main/String%20function%20with%20POSITION%20in%20place%20of%20LOCATE.png)

### String function with POSITION Use case
![](https://github.com/Ebenezer080925/Ogundaisi-Ebenezer---Boycode---4.0-Data-analysis-Cohort/blob/main/String%20function%20with%20POSITION%20Use%20case.png)

## String function with CONCAT
### Combining multiple text columns (First and Last name) into a single, professional full-name field for cleaner reporting.
![](https://github.com/Ebenezer080925/Ogundaisi-Ebenezer---Boycode---4.0-Data-analysis-Cohort/blob/main/String%20function%20with%20CONCAT.png)

## Case Statement
### Using simple CASE logic to create a binary category—labeling records as 'Young' based on a specific age threshold.
![](https://github.com/Ebenezer080925/Ogundaisi-Ebenezer---Boycode---4.0-Data-analysis-Cohort/blob/main/Case%20Statement%20.png)

## Case Statement with multiple case
### Implementing multi-tiered logic to create age brackets (Young, Old, etc.), showcasing how to handle multiple conditions in a single column.
![](https://github.com/Ebenezer080925/Ogundaisi-Ebenezer---Boycode---4.0-Data-analysis-Cohort/blob/main/Case%20Statement%20with%20multiple%20case.png)

## Case Statement Use case 1
### Applying professional business logic to data: calculating tiered pay increases and bonuses based on salary ranges within a single query.
![](https://github.com/Ebenezer080925/Ogundaisi-Ebenezer---Boycode---4.0-Data-analysis-Cohort/blob/main/Case%20Statement%20Use%20case%201.png)

## Advanced Analytical SQL (Advanced SQL)

## Subqueries Inner query
### Mastering the 'Query within a Query' technique. Using subqueries in the WHERE clause to filter the demographics table based on criteria from the salary table. This runs the inner query only that i selected 
![](https://github.com/Ebenezer080925/Ogundaisi-Ebenezer---Boycode---4.0-Data-analysis-Cohort/blob/main/Subqueries%20Inner%20query.png)

## Subqueries Total query 
### This runs the total subquery
![](https://github.com/Ebenezer080925/Ogundaisi-Ebenezer---Boycode---4.0-Data-analysis-Cohort/blob/main/Subqueries%20Total%20query.png)

## Subqueries AVG_MAX_AGE
### Performing advanced nested aggregation—calculating the average of maximum values by treating a subquery as a temporary table.
![](https://github.com/Ebenezer080925/Ogundaisi-Ebenezer---Boycode---4.0-Data-analysis-Cohort/blob/main/Subqueries%20AVG_MAX_AGE.png)

## Windows function
### Introducing the OVER() and PARTITION BY clauses. This allows for calculating aggregates (like average salary) while still keeping individual rows visible.
![](https://github.com/Ebenezer080925/Ogundaisi-Ebenezer---Boycode---4.0-Data-analysis-Cohort/blob/main/Windows%20function.png)

## Windows function Over, Partition rolling total
### Calculating a 'Rolling Total' by partitioning data by gender and ordering by ID—a key technique for tracking cumulative business metrics over time.
![](https://github.com/Ebenezer080925/Ogundaisi-Ebenezer---Boycode---4.0-Data-analysis-Cohort/blob/main/Windows%20function%20Over%2C%20Partition%20rolling%20total.png)

## Windows function row_number
### Using the ROW_NUMBER() function to assign unique sequential integers to every row, which is essential for data deduplication and pagination.
![](https://github.com/Ebenezer080925/Ogundaisi-Ebenezer---Boycode---4.0-Data-analysis-Cohort/blob/main/Windows%20function%20row_number.png)

## Windows function row_number ORDER BY
### Using ROW_NUMBER() with PARTITION BY to assign a unique, sequential rank to every row within a group. This is the standard method for identifying the 'first' or 'most recent' record in a dataset.
![](https://github.com/Ebenezer080925/Ogundaisi-Ebenezer---Boycode---4.0-Data-analysis-Cohort/blob/main/Windows%20function%20row_number%20ORDER%20BY%20.png)

## Windows function row_number ORDER BY, RANK
### Introducing RANK(). This image highlights the difference in ranking logic—where duplicate values receive the same rank, and the next rank is skipped (e.g., 1, 2, 2, 4).
![](https://github.com/Ebenezer080925/Ogundaisi-Ebenezer---Boycode---4.0-Data-analysis-Cohort/blob/main/Windows%20function%20row_number%20ORDER%20BY%20%2CRANK.png)

## Windows function row_number ORDER BY, RANK, DENSE_RANK
### The complete ranking comparison. This demonstrates DENSE_RANK(), which assigns the same rank to duplicates but does not skip numbers (e.g., 1, 2, 2, 3), providing a continuous numerical sequence.
![](https://github.com/Ebenezer080925/Ogundaisi-Ebenezer---Boycode---4.0-Data-analysis-Cohort/blob/main/Windows%20function%20row_number%20ORDER%20BY%20%2CRANK%2C%20DENSE_RANK.png)

## CTEs Inner Query
### Using the WITH clause to create a named temporary result set. This allows for complex aggregations (like averages and counts) to be stored in a 'virtual table' that can then be queried normally, significantly improving code readability. But this query i Highlighted is running thet inner query for you to see the beauty
![](https://github.com/Ebenezer080925/Ogundaisi-Ebenezer---Boycode---4.0-Data-analysis-Cohort/blob/main/CTEs%20Inner%20Query.png)

## CTEs Total Query
### this is the result of running the entire subqery very fast to query esy to read and understand what the query is talking and easy to debug
![](https://github.com/Ebenezer080925/Ogundaisi-Ebenezer---Boycode---4.0-Data-analysis-Cohort/blob/main/CTEs%20Total%20Query.png)

## CTEs selecting specific column
### Demonstrating the power of CTEs for multi-layered analysis—first aggregating data within the CTE and then performing a secondary calculation (like a grand average) on those results.
![](https://github.com/Ebenezer080925/Ogundaisi-Ebenezer---Boycode---4.0-Data-analysis-Cohort/blob/main/CTEs%20selecting%20specific%20column.png)

### CTEs is Immediately after
### whenever a inner query is ran inside a CTE statement the column cannot be called back after the query that is after the semi-colon
![](https://github.com/Ebenezer080925/Ogundaisi-Ebenezer---Boycode---4.0-Data-analysis-Cohort/blob/main/CTEs%20%20is%20immediately%20after.png)

## CTE multiple CTEs
### A showcase of advanced query modularity. Defining two separate CTEs—one for demographic filtering and one for salary filtering—and then joining them together in the final statement. This 'building block' approach is a best practice for complex data engineering.
![](https://github.com/Ebenezer080925/Ogundaisi-Ebenezer---Boycode---4.0-Data-analysis-Cohort/blob/main/CTEs%20multiple%20CTEs.png)

## 8. Procedural SQL & Session Management

## Temporary table
### Building a TEMP TABLE to hold transient data. These tables are session-specific, meaning they offer a sandbox environment to manipulate data without affecting the permanent database schema.
![](https://github.com/Ebenezer080925/Ogundaisi-Ebenezer---Boycode---4.0-Data-analysis-Cohort/blob/main/Temporary%20table.png)

## Temporary table use case
### A real-world application of temporary storage. I used a SELECT INTO approach to quickly grab all employees with salaries over 50k and store them in a temporary table for immediate, focused analysis.
![](https://github.com/Ebenezer080925/Ogundaisi-Ebenezer---Boycode---4.0-Data-analysis-Cohort/blob/main/Temporary%20table%20Use%20case.png)

## STORED PROCEDURES syntax format
### "An educational look at the structural anatomy of a Stored Procedure. This covers defining the language (PL/pgSQL), setting up parameters, and using dollar-quoting ($$) to wrap the procedural body.
![](https://github.com/Ebenezer080925/Ogundaisi-Ebenezer---Boycode---4.0-Data-analysis-Cohort/blob/main/STORED%20PROCEDURES%20Syntax%20format%20%20.png)

## STORED PROCEDURES
### A practical implementation of automation. Here, I created the large_salaries procedure to encapsulate a specific query logic, which can now be executed instantly with a simple CALL command.
![](https://github.com/Ebenezer080925/Ogundaisi-Ebenezer---Boycode---4.0-Data-analysis-Cohort/blob/main/STORED%20PROCEDURES%201.png)

## Data Cleaning

## Data cleaning and duplicate creation
### Instead of working on the original "live" data, I created a safe "staging" copy. This acts like a rough draft or a sandbox where I can clean and delete data without the risk of losing the original, important records
![](https://github.com/Ebenezer080925/Ogundaisi-Ebenezer---Boycode---4.0-Data-analysis-Cohort/blob/main/Data%20cleaning%20and%20duplicate%20creation.png)

## Data Cleaning inserting into duplicate
### This is the process of moving all the messy information from the original file into my new "staging" area. It ensures I have a full dataset to work with in my controlled cleaning environment
![](https://github.com/Ebenezer080925/Ogundaisi-Ebenezer---Boycode---4.0-Data-analysis-Cohort/blob/main/Data%20Cleaning%20inserting%20into%20duplicate%20.png)

## Checking Duplicate row
### Before deleting anything, I ran a search to look specifically for those "ID numbers" higher than 1. This allowed me to double-check and confirm that these rows truly were identical mistakes before I removed them.
![](https://github.com/Ebenezer080925/Ogundaisi-Ebenezer---Boycode---4.0-Data-analysis-Cohort/blob/main/DC%20checking%20Duplicate%20row.png)

## Checking the row with duplipcate value 
### I used a "temporary logic block" (CTE) to neatly organize the repeat rows. Think of this like putting all the "double-printed" pages of a document into a separate folder so I can see exactly how many there are
![](https://github.com/Ebenezer080925/Ogundaisi-Ebenezer---Boycode---4.0-Data-analysis-Cohort/blob/main/DC%20checking%20the%20row%20with%20duplicate%20value.png)

## Adding row_number
### I gave every row a "ID number" based on how many times that specific piece of information appeared. If a row is assigned the number "2" or "3," it tells me immediately that this is a repeat that needs to be checked.
![](https://github.com/Ebenezer080925/Ogundaisi-Ebenezer---Boycode---4.0-Data-analysis-Cohort/blob/main/DC%20adding%20row_number.png)

## Removing the duplicate row
### This is the "cleanup" phase where I officially deleted the extra copies. By doing this, I ensured that every person or transaction in the database is only counted once, which makes the final analysis accurate
![](https://github.com/Ebenezer080925/Ogundaisi-Ebenezer---Boycode---4.0-Data-analysis-Cohort/blob/main/DC%20removing%20the%20duplicate%20row.png)

##  Trimming the company column
### To remoove every Unnecesary space in the space 
![](https://github.com/Ebenezer080925/Ogundaisi-Ebenezer---Boycode---4.0-Data-analysis-Cohort/blob/main/DC%20trimming%20the%20company%20column.png)

## Different name for same industry
### Sometimes the same industry is typed differently, like "Crypto" and "CryptoCurrency." I went through and renamed them all to one standard name so that when I count them later, the totals are correct
![](https://github.com/Ebenezer080925/Ogundaisi-Ebenezer---Boycode---4.0-Data-analysis-Cohort/blob/main/DC%20different%20name%20for%20same%20industry.png)

##  Trimming removing the "." in after United state
### Computers think "United States." and "United States" are two different countries because of the tiny period at the end. I "trimmed" off those extra dots and spaces so the computer recognizes them as one single country
![](https://github.com/Ebenezer080925/Ogundaisi-Ebenezer---Boycode---4.0-Data-analysis-Cohort/blob/main/DC%20trimming%20removing%20the%20.%20in%20after%20United%20state.png)

## Error with Date
### Real-world data often contains "corrupted" entries (like text where a number should be). I documented the specific error messages I encountered, which proves I can identify and fix technical bugs during the data transformation process
![](https://github.com/Ebenezer080925/Ogundaisi-Ebenezer---Boycode---4.0-Data-analysis-Cohort/blob/main/DC%20Error%20with%20date%20.png)

## Convert date column to date datatype
### Databases often treat dates as simple "text" (like a name), which makes it impossible to sort them by month or year. I used logic to transform these text strings into actual "Date" formats that the computer can recognize for time-based analysis
![](https://github.com/Ebenezer080925/Ogundaisi-Ebenezer---Boycode---4.0-Data-analysis-Cohort/blob/main/DC%20convert%20date%20column%20to%20date%20datatype.png)

## Finale Date Value 
### After performing the conversion, I ran a final check to ensure every single date in the system followed the exact same pattern (YYYY-MM-DD). This ensures that a search for "March 2026" doesn't miss any records due to a typo
![](https://github.com/Ebenezer080925/Ogundaisi-Ebenezer---Boycode---4.0-Data-analysis-Cohort/blob/main/DC%20finale%20Date%20value.png)

## Dropping the row column and checking our finale cleaned Dataset
### During the cleaning process, I used extra "helper columns" (like row numbers) to find mistakes. Now that the data is perfect, I deleted those tools to keep the dataset clean, lightweight, and ready for use in a report or dashboard
![](https://github.com/Ebenezer080925/Ogundaisi-Ebenezer---Boycode---4.0-Data-analysis-Cohort/blob/main/DC%20Droping%20the%20row%20column%20and%20cheking%20our%20final%20cleaned%20Dataset.png)

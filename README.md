# Data-Science-assignment-1
For this drill, you'll work with data from the City of New York, which has provided statistics on baby names since 2011. You'll need to use the string functions that you learned about to tidy up the text fields in this workbook.

Requirements
Convert the values in the Gender, Ethnicity, and Child's First Name columns to proper case.
Create a column called Name beginning letter. Fill your new column with just the first letter of each first name.
There is some inconsistency in the Ethnicity column. In 2012, records are as follows: ASIAN AND PACI, BLACK NON HISP, and WHITE NON HISP. In other years, records feature ASIAN AND PACIFIC ISLANDER, BLACK NON HISPANIC, and WHITE NON HISPANIC. Use the SUBSTITUTE function to replace the first set of labels with the second set.
 
 
 Assgn. 2 
 In cells L3:M4, use INDEX and MATCH to find the 2011 and 2015 populations of Michigan and Arizona. You should be able to take the formula in cell L3, drag it to the remaining cells with the fill handle, and get the right answer each time. Hint: Use a combination of absolute and mixed cell references.
Find the 2014 populations of the most populous states in cells L9:L13, and sum them in cell L14. Return any errors with a custom message in the cell, and ensure that L10 returns no errors. Note: Canada is not a state, and it doesn't appear in the data. If you have an unhandled error in that cell, it will break the total formula in cell L14.
Write a function to generate the average three-year population in Ohio, starting in 2012. This function should be dynamic. It should use the references in cells L17:L19 so that these inputs can change and the resulting calculation can also change.
Sort the population table in random order by placing a random number generator in column A

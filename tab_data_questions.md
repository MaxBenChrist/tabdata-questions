The following list serves as a baseline list of questions that are used to get familiar with new tabular data sources as a Data Scientists. 

# Table level:

First the different tables themselves and how they relate to each other are under investigation:

*   Association: How can the different tables be associated? How can one construct keys to associate them?
*   Origin: Where do the different tables originate from? This could relate to technical systems, departments or processes.
*   Construction: Were they joined from other tables or were they created from database dumps?
*   Stakeholder: How were the tables collected? Which organizations, departments or persons were involved?

#  Column level: 

Now we understand the tables which is why we start asking questions about the different columns:

*   Purpose: What is the meaning of the different columns? Which information should they contain?
*   Processes: How was the data for this column collected? Was it generated automatically or by human?
*   Range of values: What is the expected range for the different values? This information can be used to detect outliers.

#  Cell level:

Now we have a deeper understanding of both columns and tables which is why we start caring about individual values:

*   Meaning of values: What does the different values mean? What is the meaning of abbreviations? 
*   Ordering of values: Is there a natural ordering in certain classes?
*   Meaning if NAs/missing values: Is there really missing information or was the information hidden by purpose?
*   Meaning of certain samples/rows: Is sample/row XYZ ok or an outlier?

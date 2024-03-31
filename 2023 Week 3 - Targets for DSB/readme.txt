
Inputs
-The same transactions file as the first week 
-Quarterly Targets dataset 

Requirements

Input the data
For the transactions file:
  Filter the transactions to just look at DSB 
  These will be transactions that contain DSB in the Transaction Code field
  Rename the values in the Online or In-person field, Online of the 1 values and In-Person for the 2 values
  Change the date to be the quarter
  Sum the transaction values for each quarter and for each Type of Transaction (Online or In-Person)
For the targets file:
  Pivot the quarterly targets so we have a row for each Type of Transaction and each Quarter
  Remove the 'Q' from the quarter field and make the data type numeric
  Join the two datasets together
  Remove unnecessary fields
  Calculate the Variance to Target for each row (help)
Output the data

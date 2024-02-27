Link: https://preppindata.blogspot.com/2024/02/2024-week-6-staff-income-tax.html

The end of January in the UK (where Prep Air is based) is when residents have to submit their income tax returns by. To help our team, we've offered to summarise their tax position for them. The UK income tax works by bands. Here's a summary table showing the percentage of tax for each pound earned in that bracket: 
![tax bands](https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEjb4x01iCIrMGNS8qxplMNJoXRma3YZz9FdpBs39FlkfxspveNmDIJQS4zz9PvsritFkVBXq4XK9EuegpWHrtcpLkFtaLRHQIzm0dYgjLjxAQAIzJyojyWuhcM24qFF503Mv8rc4O1GxDYJaNnGrxxYYxZ0EgLzCA7RM2WRL5e1-Vi-IhBIMs8U8PYbsKQS/s952/Screenshot%202024-01-28%20at%2017.51.57.png)
For example, if I earned £12,571. I would pay £0.20 of tax in total: £0 for the first £12,570 earned and then 20% of the £1 in the next tax band. 

Input
One csv file containing the monthly salary for staff. If any team member has a change in their pay, their new salary is recorded as a later record but the input contains their former record based on what they would have been paid.

- Add a row number to the data set
- Find the latest row (largest row number) to capture the individuals correct salary information
- Find each team member's annual salary
- Find each team member's maximum tax band based on their annual salary
    20% rate
    40% rate
    45% rate 
- Work out how much tax an individual paid for each of the % bands. Call these fields:
    20% tax rate paid
    40% tax rate paid
    45% tax rate paid
- Total the tax paid across all three % bands. Call this field 'Total Tax Paid' 

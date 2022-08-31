# Finance-Report-DAX
Financial reporting exercise: write an expression in DAX
The report answers your manager's main questions:

-Which month and year made the biggest profit?

The profit graph by date shows that December 2014 brought in the biggest profits.

-In which country did the company have the most success?

Europe, especially France and Germany.

--In which product and segment should the company continue to invest?

The profit graph by product and segment shows that then the company should continue to invest in the Paseo product and target the small business and government segments.

Key points:
DAX allowed to add up all the numbers in the "Units sold" column:
Total Units Sold = SUM(financials[Units Sold])    
 Create a calendar table with all dates between January 1st 2013 and December 31st 2014
Calendar = CALENDAR(DATE(2013,01,01),Date(2014,12,31))    


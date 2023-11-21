# WSDA-SQL-portfolio
Hello,
This is a repository contains SQLite queries to showcase my analysis on WSDA music data investigating financial discrepancies by joining the customer, invoice and employee tables.
The first couple of SQL queries show basic queries to determine average sales by city, transactions between 2011 and 2012, number of albums per artist while the last 2 queries 
investigate the financial record to determine what transactions done by were too far from the average sale between 2011 and 2012
The query identified the transaction done by Jane Peacock for John Doeein with invoice id 413 as the most unusual from average sales and after digging into the invoice line table, 
it became obvious that invoice 413 did not exist with any sales record and Jane Peacock received commission that she should not have been paid.

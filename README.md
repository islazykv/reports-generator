# Reports Generator
<div align = "justify">
The following project had a purpose to get some experience with Django and to implement data-science python libraries such as pandas, matplotlib and seaborn. The main functionality of this project allows a user to generate PDF files based on the already provided transactions. Transactions are for the whole year of 2021. A user selects a date from and a date to, choose a char type (either bar, pie or linear) and groups the data by transaction ID or sales date. 

## Used libraries
Necessary libraries to launch this project can be found in: requirements.txt file. To install them all please use the command: "pip install -r requirements.txt".

## Presentation
You can launch the project by going to the src via console and typing "python manage.py runserver", then refer to the link to the localhost. So far only the login functionality has been created (without the register functionality) hence use the login provided in the login page.

<img width=100% align="center" src="src\sample\1-login.png"/>
  
When a user is logged in, a home page can be seen with the instructions.
 
<img width=100% align="center" src="src\sample\2-home.png"/>
  
Then, after hitting "search" button, pandas dataframes are displayed...
  
<img width=100% align="center" src="src\sample\3-dataframes.png"/>
  
... together with a generated report.
  
<img width=100% align="center" src="src\sample\4-report.png"/>
  
By clicking "Add Report" a modal pops up where a title and a description can be specified.
  
<img width=100% align="center" src="src\sample\5-report-cart.png"/>
  
The reports are generated based on the already inserted transactions from the sales page.
  
<img width=100% align="center" src="src\sample\6-sales.png"/>
  
Each transaction can be viewed further to check its details.
  
<img width=100% align="center" src="src\sample\7-sale-detail.png"/>
  
There is also a possibility to upload a CSV file (Add from file page) and then a report is generated automatically. However, a CSV file has to comply with the dataframes architecture.
  
<img width=100% align="center" src="src\sample\8-dropbox.png"/>
  
Saved reports can be viewed in the reports page. 
  
<img width=100% align="center" src="src\sample\9-reports.png"/>
  
And details of each report can be looked into.
  
<img width=100% align="center" src="src\sample\10-report-detail.png"/>
  
By clicking "PDF", an user is taken to a new tab with a PDF file ready to be printed or saved locally.
  
<img width=100% align="center" src="src\sample\11-report-pdf.png"/>



</div>

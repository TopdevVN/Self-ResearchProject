## ETL Stock price data of Big 4 companies
### Process:
**Scraping data phase with Python:** <br>
&nbsp;&nbsp;&nbsp;&nbsp; Using the _yfinance_ library in Python to scrape stock price data from Big 4 companies that have invested 
a huge amount of capital on AI recent years (2022-2025), and save the data to 4 separate Excel files. <br>
**ETL on Visual Studio phase:** <br>
&nbsp;&nbsp;&nbsp;&nbsp;**1** Create a workflow on Visual Studio (using SSIS) to Extract data from Excel files. <br>
&nbsp;&nbsp;&nbsp;&nbsp;**2** Add new columns: Company, Deviation (the difference between Close & Open price), and the price trend (increase or decrease). <br>
&nbsp;&nbsp;&nbsp;&nbsp;**3** Merge all 4 companies data, sort, add rowid and load data to the SQL server. <br> 

**Dataset:** Stock price of big 4 companies: Amazon, Microsoft, NVIDIA and Oracle.
<p align="center">
  <img width="633" height="290" alt="ETLProcessDone" 
       src="https://github.com/user-attachments/assets/1a0d7508-cbba-499b-9a68-9cfcb4910dbc" />
</p>
<br>
<p align="center">
  <img width="633" height="290" alt="QueryData" 
       src="https://github.com/user-attachments/assets/a9c11617-af36-4878-b879-f53150c61548" />
</p>


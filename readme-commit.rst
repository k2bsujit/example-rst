.. highlight:: rst

============================
reStructuredText with Sphinx
============================

-----------------
Setting up Sphinx
-----------------

^^^^^^^^^^
Windows XP
^^^^^^^^^^ 
 
 Index Calculation:
  ==================
  -   Get all history data of BTC coins using cURL "http://coincap.io/history/BTC"
  -   Store Coin data based on the date value
  -   Store all volume data in descending order
  -   Get last 30 days volume record
  -   Sum the last 30 days volume data
  -   Count the volume record
  -   Find the average of last 30 days volume
  -   Store the volume data greater than zero value
  -   Get all coin data symbols and name using cURL "http://coincap.io/map"
  -   Get all history data of coins using cURL ""http://coincap.io/history/COIN_SYMBOL"
  -   Calculate percentage based on BTC
  -   Find and store Market Cap based on the percentage greater than 0.01%
  -   Store Market Cap value
  -   Sort array values to find first 10 rank records 
  -   Get first 10 rank records to find the average
  -   Store first 10 rank coins & percentage value
  -   Find total count of 10 records
  -   To find Index composition in percentage by finding average
  -   Multiply percentage value with Market cap value
  -   Find Index value by adding 10 coin records
  -   Divide the calculated value by the static number 23,834,013
  -   Store all Coins Total Market Cap Records
  -   Insert the calculated Index into the database  
  
  Graphical Section
  =================
  Line Chart
  ==========
  Index variation by day
  ----------------------
  X-axis - Timestamp value
  Y- axis- Index value
  
  Based on the Index value calculation, the graph shown using High Charts.
  
  Pie Chart
  =========
  Martket Cap percentage record (Individual day record)
  -----------------------------------------------------
  Graph represents top 10 coin records of the day with Coin name and Marketcap percentage value.
  Graph drawn using High Charts.
  
  Coin Listing
  ============
  List top 10 coin name and its marketcap percentage value.
  
  Tabular column (Index percentage changes)
  =========================================
  List the Index value changes based for 24 hours, Week, Month, 3 Months and Year.

  Schedule Cron:
  ==============
  Run cron job for each 15 mins to store all the index records to track the rank and its percentages.

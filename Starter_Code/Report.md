#Analysis report

**Collected the Data

Used the Pandas read_csv function and the Path module to import the data from bitstamp.csv file, and created a DataFrame called bitstamp and coinbase.



**Prepared and cleaned the data for analysis:

- Replaced or drop all NaN, or missing, values in the DataFrame.

- Used the str.replace function to remove the dollar signs ($) from the values in the Close column.

- Converted the data type of the Close column to a float.

- Reviewed the data for duplicated values.



**Analyzed the Data:

Chose the columns of data on which to focus your analysis.

created summary statistics and plotted the data.

Focused analysis on specific dates.

Calculated the arbitrage profits.




### Analysis findings#Analysis report

**Collected the Data

Used the Pandas read_csv function and the Path module to import the data from bitstamp.csv file, and created a DataFrame called bitstamp and coinbase.

![read csv data](https://github.com/MxP05/Challenge3/blob/main/Starter_Code/step1.jpg?raw=true)



**Prepared and cleaned the data for analysis:

- Replaced or drop all NaN, or missing, values in the DataFrame.

- Used the str.replace function to remove the dollar signs ($) from the values in the Close column.

- Converted the data type of the Close column to a float.

- Reviewed the data for duplicated values.

![cleaned and prepared data for analysis](https://github.com/MxP05/Challenge3/blob/main/Starter_Code/step2.jpg?raw=true)

**Analyzed the Data:

Chose the columns of data on which to focus your analysis.

created summary statistics and plotted the data.

Focused analysis on specific dates.

Calculated the arbitrage profits.

![Spread visualization](https://github.com/MxP05/Challenge3/blob/main/Starter_Code/step3.jpg?raw=true)

![graphed spread](https://github.com/MxP05/Challenge3/blob/main/Starter_Code/step4.jpg?raw=true)

![Cumulative profit graphed](https://github.com/MxP05/Challenge3/blob/main/Starter_Code/step5.jpg?raw=true)


### Analysis findings

 After reviewing, and comparing the profit information over different periods of time, the obvious trend which i observed was that as time and trading progressed the profitable arbitrage moments declined, the month of janauary sees the most arbitrage opportunities, and the month of march the least.
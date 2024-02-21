# Python Liquidity
## Description
The following project compares the bid ask spreads and turnovers of various ETP crypto products. 
## How to use
- The data file is a prerequisite for this code to run. The data file has to be in the same folder as this ipynb file or the pandas read excel function will not register. As of right now I have reduced the file name from ProductComparison.xlsx to pc.xlsx to make it easier. But depending on the file name, this line will change (I have commented down the lines that need to be changed).

 - Pandas and matplotlib were utilized in order to work with the data and plot the resulting figures.

 - There are two dictionaries in the beginning, the months were used to simplify the approach of dates, thus it does not need to be changed. However, sharename has been updated to the most current product tickers and their families. With the addition of new products, this needs to be updated with the format of 'Ticker':'Product Family'. 

 - The pdf function to output all the images as a single pdf needs to be changed. Currently, a package that identifies the size of the images and sizes them correctly has not been found. Will update soon but in the meantime have used smallpdf online in order to make a single pdf. 

 - Nothing else in this code needs to be changed as it will read all the files, name it accordingly, and output the data. The only thing to look out for is the product family which may not be shown in the legend of the graph. This is updated as of April, 2022. 
 
 * Note to make sure this works properly we just have to restart kernel and update all cells. 

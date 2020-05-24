# Challenge (Stock Analysis)
For this analysis, I refactored the code that I had written for Steve to run an analysis on all green stocks. A brief summary of the new code is as follows. The first part involves formatting the output sheet to have a title (Cell A1) and column headers. I then initialized the ticker symbols as an array. After this, I found the number of the rows needed to loop through on the sheets containing the data. I then initialized the ticker array index as a variable equal to zero, and initialized total volume, starting price, and ending price as arrays. 

The first for loop I created ran through the total volume for each ticker and set them all equal to zero. The next for loop I created loops through all rows of the data and contains 3 if-then statements. The first adds the current volume cell to the total volume for that ticker. The next determines whether the row contains the starting price for that particular ticker. The final statement determines if the row contains the ending price for the current ticker. If this is the case, then the ticker index is increased by one. This process is repeated for each row that the for loop loops through.

The final portion of the code deals with outputting the data into the output sheet, and formatting it once it is in the output sheet. 

Note: all code is stored in the "AllStocksAnalysisRefactored()" subroutine.

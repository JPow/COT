# COT
Commitment of Traders (COT) report analysis

This code downloads committment of traders data using Nial Delventhal's cot_report python library to download reports into a data frame and perform analysis on the Open Interest data.  

Data is indexed by market based on key words

Commodities Open Interest (Indexed or Actual) are displayed in matplotlib line graphs.

Loop through a list of markets at once.

Dependencies:
pandas
matplotlib
numpy
cot_reports - https://github.com/NDelventhal/cot_reports (see ReadMe and review licence) 

Please let me know how to improve the code, feel free to contribute.

Disclaimer: the code has not be validated for accuracy, the code doesn't clean the data for you, you should not use the code for trading but can use it to see how open interest is fluctating over a timescale you set limited by data available.

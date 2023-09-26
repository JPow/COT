# COT
Commitment of Traders (COT) report analysis

This code downloads committment of traders data using Nial Delventhal's cot_report python library to download reports into a data frame and perform analysis on the Open Interest data.  

Data is indexed by market

Groups of commodities are displayed in matplotlib line graphs in bulk using a for loop.

Dependencies:
pandas
matplotlib
numpy
cot_reports - https://github.com/NDelventhal/cot_reports (see ReadMe and review licence) 

Disclaimer: the code has not be validated for accuracy, the code doesn't clean the data for you, you should not use the code for trading but can use it to see how open interest is fluctating over a timescale you set limited by data available.

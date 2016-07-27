Begin: 7/26/2016
Last Update: 7/27/2016

Log:
7/26/2016 - raw data for all weekly options (2006-2016) added
7/27/2016 - ingester added - produces intermediate data set

1. Intro:
Project aims to look at return properties of weekly options versus monthlies versus quarterlies. Comparisons to traditional option model predictions, and evidence for standard assumptions examined.

2. Data
	a. Raw
		i. Weekly Options - saved in format mmddyyyytt.xlsx - contains 37 option fields presented as a snapshot from BBG
	b. Intermediate
		ii. weeklyOptionData.txt - tab separated format of all weekly option data. Produced by ingester.py

3. Source
	a. Python
		i. ingester.py (inputs Weekly Options data, outputs weeklyOptionData.tx) pulls data from excel sheets into a square data table.
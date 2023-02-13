Socioeconomic Team:

![](https://lh5.googleusercontent.com/0Lg7WF0eyRxdyfBCww1nWIXoI0IJuX7kt6iTyA0EX1jeqnleRjlAUSXa1_ZovhIFY4Rts0j35SabYzZ_ke3px3eZtXigYH-m48l4F4-JT0TjYPNH6m2569ULv5hHipRMK8hWNMngVwJJqHV18KPoBA)

1.  First we looked at the data from the past teams 

a. [Maher_Main_File.xlsx and Omittedna_norm.csv README](https://docs.google.com/document/d/1DtpDRDwl1Bi7LM1L_BKBpT4tb1XteK66sXaMM6imLGE/edit?usp=sharing)

b. Files from the Fall 2020 team are located in this [folder](https://drive.google.com/drive/folders/1NO0Z6YYfH37rBfuN0rfy4SgAR26NRO3q?usp=sharing). Download [Data and Code.zip](https://drive.google.com/file/d/1gAD7z68wj3nfzXiNM0Te-0tYCLza9Tuo/view?usp=sharing)

2.  Next we merged Maher_Main_File.xlsx and Omittedna_norm.csv

a.  Python file for merge can be found in the shared folder. 

b.  Merged dataset (Merge_Maher_omit.xlsx)

3.  Then we merged a FIPS code on to the MergedMaherOmit file

a.  FIPS codes.csv

b.  Merged File (MMO_FIPS.csv)

4.  Then we found a UCR dataset and merged it with the file in #3b

a.  Clean URC data file can be found in the shared folder. 

b.  Python file for merge

c.  Merged file (finalData.csv)

5.  Fitted a logistic regression in JMP software and Python

a.  First we did a stepwise regression

b.  Final Regression Code  (Python file -- LogisticRegression.ipynb)

6. Supply the final XLS file (with probabilities) to the next team (PredictionFilterData.xlsx).

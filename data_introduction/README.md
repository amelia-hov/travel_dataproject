# travel_dataproject

08/07 - Looked into how to import a file into panda, but wasn't sure where to start the coding process.
import pandas as pd
excel_file_path = C:\Users\ameli\OneDrive\Documents\UNSW\CODE1161\A1
df = pd.read_excel(excel_file_path)
print(df.head(200))
This is the code that I think should be able to import my Excel file to the pandas.

10/07 - Imported data and changed all the information to my own data name and started creating the graphs and charts. I also changed all the titles of the columns and tried to figure out a way to skip the rows to 131 - 251. Names of Y Value (T) means Temporary, (P) means Permanent,

14/07/ - Changed the name of my sheets, and imported multiple sheets of my data into pandas just to get a gist of comparing the data and trying to spot any weird increases or decreases in visa uses.

21/07 - Tried playing around with pandas again. Need to understand each function. Will try to make some maps and histograms tmr.

23/07 - Made more tables using data of other states by copying and pasting the functions and changing what needed to be changed.

04/08 - Realised that my data was only the amount of DEPARTURES. I decided to incorporate the use of the amount of ARRIVALS so that I can compare the data and find the problems that might've caused the data to increase or decrease. Today I successfully made a map of Aus.

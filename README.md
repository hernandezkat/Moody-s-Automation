# Moody-s-Automation
The purpose of this project is to preprocess 6 files received from IT and prepare 7 files for an API Liberty utilizes from Moody's. The process the code is 
intended to follow utilizes the following steps:
1. Append 6 GIBSS files into 1
2. Filter data according to Statement Type, Statement Month and Product Type
3. Merge data from an existing excel file and output for manual updates. 
4. Read the file back into Python and split the data by the three Product Types
5. Output this split file into one file according to Principal ID
6. Create new Series calculations, which can be found in word document. 
7. Divide all data within DataFrame by 1,000
8. Output 7 API CSV files intended for usage in the Moody's API

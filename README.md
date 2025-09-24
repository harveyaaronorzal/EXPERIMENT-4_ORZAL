`ECE2112: Advanced Computer Programming and Algorithms`
## EXPERIMENT 4: DATA WRANGLING AND DATA VISUALIZATION

### I. Intended Learning Outcomes:  

1. To identify the codes and functions needed in cleaning and visualizing data
2. To be able to apply and use the different codes and functions in creating a Python program that will
be used in data wrangling and data visualization

### II. Instructions:

Download the ECE Board Exam 2 dataset found on this link: bit.ly/ECEBoardExamDataset and write a Python script/code in the Jupyter Notebook to do the given problems. You may submit your Jupyter notebook in the dedicated submission bin.

### III. ECE BOARD EXAM PROBLEM: 
Using data wrangling and data visualization technique with
storytelling, analyze the data and present different (i) data frames; and (ii) visuals using the dataset given.
1. Create the following data frames based on the format provided:  

Example: Vis = [“Name”, “Gender”, “Track”, “Math<70”]; hometown is constant as Visayas  

Output:  

<img width="751" height="141" alt="image" src="https://github.com/user-attachments/assets/db0f8fce-93f0-4c26-95d9-dd49d849e319" />

a. Filename: Instru = [“Name”, “GEAS”, “Electronics >70”]; where track is constant as Instrumentation and hometown Luzon

<img width="708" height="580" alt="image" src="https://github.com/user-attachments/assets/aa0a8411-0769-45a8-9130-f7d39582d811" />  

- The program uses the pandas library (imported as pd) to work with data from an Excel file named "board2.xlsx". The file is read into a DataFrame called "boards". A filter is then applied with .loc[ ] to keep only the rows where the Track is "Instrumentation", the Hometown is "Luzon", and the Electronics score is above 70. From this filtered dataset, only the columns "Name", "GEAS", and "Electronics" are selected. The result is saved into a new DataFrame named "Instru", which is displayed to show the students who meet the given conditions along with their GEAS and Electronics scores.

b. Filename: Mindy = [ “Name”, “Track”, “Electronics”, “Average >=55”]; where hometown is constant as Mindanao and gender Female  

<img width="1001" height="763" alt="image" src="https://github.com/user-attachments/assets/f4f53db9-5d47-4efb-bf1e-d7c58e01893a" />

- The code begins by importing the pandas library as pd and reading student records from the Excel file "board2.xlsx". It then computes the average of each student’s scores in Math, Electronics, GEAS, and Communication, storing the result in a new column named "Average". Afterward, the dataset is filtered to include only female students from Mindanao whose Average is at least 55. From these filtered entries, only the columns "Name", "Track", "Electronics", and "Average" are kept, creating a new DataFrame called "Mindy". The output presents the students who satisfy all these requirements.

### IV. Conclusion  

- The activities successfully met the objectives by showcasing how different codes and functions in the Pandas library are applied to real data. Through the use of functions like read_excel, column computations, and .loc[] filtering, the programs identified and extracted specific student groups based on given conditions. New DataFrames such as "Instru" and "Mindy" were created to present organized and relevant outputs. These tasks illustrate how Pandas can both process and simplify data, making analysis more efficient and meaningful. Overall, the objectives were achieved by identifying key Pandas functions and applying them effectively in Python programs for data handling and filtering.

Harvey Aaron E. Orzal  
2ECE - B




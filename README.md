1.Name of the Project -->  Cricinfo Extracter (Cricinfo 2019 WorldCup Data Extracter)

2.Purpose -->
2.1The purpose of the project is to extract the information of Worlcup 2019 from Cricinfo snd present that info in the form of excel and pdf scorecards.
2.2The real purpose of the project is to learn how to extract the information from a website and get experience with it.

3.Reason --> A very good reason for me to make this project is to learn javascript.

4.Programming Language --> JavaSript
 
5.The dependencies used by me while making this project are :- 
5.1.minimist 
5.2.axios 
5.3.jsdom 
5.4.excel4node
5.5.pdf-lib
5.6.fs -> this library is pre installed in node
5.7.pdf -> to give the path name of files

6.Activity --> The tasks performed while making the project are -->
              6.1.Read data from the source : Cricinfo Worlcup 2019 (using the axios library)   
              6.2.Process the data we read from website : Get all the teams( using the jsdom library)
              6.3.Change the information extracted (Array Manipulation)
              6.4.Write processed data in excel (Match result per team in their own sheet)
              6.5.Create folder :one for each team
              6.6.Write files: PDF files for scorecard of each match in relevant folder

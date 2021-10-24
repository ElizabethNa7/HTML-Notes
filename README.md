# HTML-Notes

### Link: https://elizabethna7.github.io/HTML-Notes/

## Environment:
IDE used: Visual Studio Code Language: Python3

## To start/run the program:
Run the code, and you will be prompted to input the data in the terminal.

Please type/paste the data following this format: "TITLE,DATE,AUTHOR,LENGTH", with dates formatted as "mm/dd/yyyy" e.g. "02/14/1856"

Additionally, every book and its information should be in one new line, for example: Carrie,06/13/1982,Steven King,762 The Stand,01/01/1984,Steven King,1200 The Hunger Games,11/12/2013,Suzanne Collins,600 When done press enter and then CTRL+D if you are on Mac, or CTRL+Z if on Windows.

## Overall format of code
There are two function definitions at the top (one_author and multiple_authors). one_author is used if there is clearly only one author that wrote the most amount of books. multiple_authors is used if there is more than one author that wrote the most amount of books.

Before either of these are called, there is a general setup to organize the input, verify the inputted authors, and find the author(s) that wrote the most books. Depending on whether there is more than one author, either one_author() or multiple_authors() is then called.

Note: For multiple_authors(), it will find the dates of the books written by the targetted authors and print one sentence out based on the oldest book within those authors books.

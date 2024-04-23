Here is the Google Colab link where I coded to change the pdf files to csv files:
[https://colab.research.google.com/drive/1jxg0wmys0NHMYpKIDWri5F-dgKht0co2?usp=sharing](url)
The steps which I did for converting pdf to csv are:
1. First I installed the fitz library using pip.
2. Then installed frontend and pymupdf similarly.
3. I opened the pdf using fitz.open() function
4. then calculated the number of pages in the file by using .page_count function.
5. And then ran a for loop of that range reading each page and using the command .find_tables function to convert the tables of pdf to dataframe.
6. Then concatting the dataframes into one.
7. Then converting it to csv file using .to_csv function.

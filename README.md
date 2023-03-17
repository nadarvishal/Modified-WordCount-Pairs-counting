# Modified-WordCount-Pairs-counting

Introduction:

For this Homework, we are using are the text transcriptions of the State of the Union Addresses given by Presidents to Congress since 1790 to the present year as the dataset. There are two parts to this Assignment. In the first part of the assignment, I have done wordcount of the data , cleaning of the data and computing the average and standard deviation of the words. In the second part of the assignment, I have converted the data into pair of words and calculated the frequency of co-occurrence of words and I have also calculated the lift of two words bigger than 3.0 .

Pre-Processing Data:

In the index page of the State of the Union Addresses, there are many individual speeches delivered by the president each year. First, I used the urlopen() method from the urllib.request.Request module to read the contents of the website and save them . With the contents, I further took out the links present in the index page using the h_ref . The links are saved in a file alllink.txt . After that I opened each link, I wrote their data onto separate text files such as “contentfile-17900108.html.txt” for the year 1790 for the sub-link http://stateoftheunion.onetwothree.net/texts/19620111.html. Like this, data of all years are separately stored in text files and then accessed using a “allnames” list which has the names of all stored txt files. Using this, I access all the data present in the speeches.

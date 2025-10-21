Project: weblog-analyzer
Aothors: David J. Barnes and Michael Kölling

This project is part of the material for chapter 7 of the book

   Objects First with Java - A Practical Introduction using BlueJ
   Seventh edition
   David J. Barnes and Michael Kölling


Purpose of project: To provide an illustration of the use of arrays.
How to start this project: Create a LogAnalyzer object.

The LogfileReader expects to read a file, weblog.txt,
containing lines of data in the format:

    year month day hour minute

month values are in the range 1-12 and day values in the range 1-31.
If the sample file cannot be found, the reader will create some simulated
data. Alternatively, use the LogfileCreator to create some random data.
Use its createFile method to give a file name and the number of entries
to create.
PART 1: with Raymond
Question 1: 18:237
Question 2: Person[] people;
Question 3: boolean[] vacant;
for( int hour = 0;hour<hourCount.length;hour++){
     if(hourCount[hour]==0)
        vacant[hour]=true;  }
{
esle
     vacant[hour]=false;
Question 4: The hourCount variable is used 5 times. Throughout the LogAnalyzer class, including 3 space brackets.
Question 5: int[] count;     boolean[] occupied = new boolean[5000];
Question 6: double[] readings = new double[60];     String[] urls = new String[90];    TicketMachine[] machine = new TicketMachine[5];
Question 7: 0 
Question 8: double[] prices = new double[50];
Question 9: we cant get the last number of the index because its always -1. 
Question 10: int hour = 0
             while(hour < hourCount.length)
             System.out.println(hour + ": " + hourCounts[hour]);
             hour==;
Question 11: 
Question 12: public LogAnalyzer( String filename)
            reader = new LogfileReader(filename);


# Election-Analysis

## Overview of project
A colorado board of election employee *Tom* was giving the task to audit the result of US congressional of Colorado, the task was to :
 1. Calculate the total number of votes cast.
 2. Get a complete list of candidates who received votes.
 3. Calculate the total number of votes each candidate won.
 4. Calculate the percentage of votes each candidates won.
 5. Determine the winner of the election based on popular vote.
 
 ## Resources
 
 -Data source : Election_results.csv
 -Software : Python 3.6.1. Visual Studio Code, 1.38.1


## Results
[here](/VBA_Challenge.xlsm.xlsm)
### the stock performance in  2017

 At first look the table below reveals that all stocks (except TERP) performed well and reflected  positive average return. DQ stock outperformed all the other stock.

 We can conclude that 2017 was a great year for the green energy industry.

 Here is the graphics that shows the results .
 
![here](/Resources/VBA%20performance%202017.png)


![here](/Resources/VBA_Challenge_2017.png)


### the stock performance in  2018

For this analysis we used the same methods, the graphics shows that the green energy industry crashed in 2018 and that all stocks went down except ENPH and RUN who outperformed well.
ENPH lost few point but stayed strong during the two years, RUN outperformed from the year 2017.

DAQO stocks did not perform well in 2018.


![here](/Resources/VBA%20performnce%202018.png)


![here](/Resources/VBA_Challenge_2018.png)





## Summary


### What are the advantages or disadvantages of refactoring code?

Code Refactoring is a way of restructuring and optimizing existing code without changing its behavior. It is a way to improve the code quality.

Code Refactoring should not be done just any time. 

Code should be refactored on the below points,
Chances of Enhancement are high
If modules have chances to add new features or functionalities then make sure design and current code is good and following Open Close Principle
Code Smell is Detected
Codes are written badly in some cases, and so many bugs are raised. In this case, fixing of bugs take too much effort. So, the root cause of bugs can be code smell. So, before fixing bugs code should be refactored.
Refactoring Improves the Design of Software
Refactoring Makes Software Easier to Understand
Refactoring Helps Finding Bugs
Refactoring Helps Programming Faster if Delivery Deadline is near.

Code should not  be refactored on the below points,
The cost of refactoring is higher than rewriting the code from scratch.
If you don't have the time to test the refactored code before release. It can introduce bugs. 
Stable code should not be refactored.




### How do these pros and cons apply to refactoring the original VBA script? 


In this challenge, we refactored the Module 2 solution code to loop through all the data one time in order to collect the same information.
It helped gain in time by making VBA run faster and englobe all the information needed and explain the finding and also clean and edit the code and make it presentable and readable.

The cons to refactoring the original VBA  was the safety, as beginner I was not feeling confident to refactor and screw all data 


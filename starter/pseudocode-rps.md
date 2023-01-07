# Data analysis pseudocode


Analyse 2 things: 
Data 
Profit/Losees

Write code to analyse records and calculate the total number of of months included on this data set

The net total amount of Profit/Losses over the entire period

The average of the changes in Profit/Losses over the entire period.

Track what the total change in profits is from month to month to then find the average

The greatest increase in profits (date and amount) over the entire period.

The greatest decrease in losses (date and amount) over the entire period.


// count how many months are in the the date set (months)
// calculate total of all monthly profits (total) 
// calculate the difference between one month and the previous month (difference)
// calculate the total of the diferences (totalDif)
// Divide totalDif by the month -1 (coz we dont count the first) ... (average) 
// checl all diffs for the largest (max)
//- which month does the max beling to? (maxMonth)
// check all diff for the smallest (min)
//- which month does the min belong to? (minMonth)
//Put all these things together in one console output (output)


let Total = 0;
for (let row = 0; row < array.length; row++) {
   
}
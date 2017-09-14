# LoyaltyOne Lightning Challenge

### Time Limit : 
25 mins - All code must be submitted at the time that staff specify.

### Challenge :
You are an Airmiles collector that loves to shop at Store X.

Store X has an airmiles offer, the only constraint in this promotional campaign is that you can’t collect miles in two consecutive days.  Each day has a different number of miles given away, and a certain number of dollars required to spend in exchange for the miles. Given that you only have n dollars to spend in total, determine the maximum number of miles you can collect.  

Given a list of tuples, with the first element of the tuple representing the number of miles to be collected and the second element representing the number of dollars required, with each tuple representing the offer that day, determine the maximum number of miles you can obtain in the entire time period. 

Using Python or Java to determine the solution. Incorrect solutions will be eliminated. The fastest solution written in each language will be selected through test cases and the solutions will be evaluated manually for complexity. The solution with the best complexity will be the winner.


### Input : 
- Budget: Integer - total amount of money to spend
- redemptionList: Integer[][]  - Each element of the list is a tuple, in which
    -   1st element is collectable # of miles, and
    -   the 2nd element is the cost.

### Output :
- maximum # of miles that can be collected

### Example :
|budget|campaign (cost, miles)|maxAM|
|---|---|---|
|10|[(3,5),(5,7)]|7|
|10|[(5,7),(10,12),(4,10)]|17|

### Submission :
- Fork the repo and create a pull request for your code.


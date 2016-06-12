# LotterySystem
Advanced lottery system intended to replace the trivial lotto 649 system. The following constraints were considered while designing the system -:
(1) Only one lottery ticket can be purchased at single time
(2) Mimimum number of tikcets that should be sold before starting a draw should be 3
(3) Winners cannot be declared if draw has not happened
(4) Same ball is not drawn twice, in order to have a unique winner in each draw
(5) Winning amount is dynamically assigned to each winner based on the total tickets sold and available prize money
(6) Every time you start a draw, the data of previous buyers and winning ball numbers are erased in order to avoid duplicacy

The working of the project is as following 
(1) As soon as you open the project, you are given the options of choosing 
        1# Purchase a ticket 
        2# Start a draw 
        3# Display the winners
(2) To begin with the first step, you must purchase a ticket (Press 1) by providing the first name of the user. With each ticket sold to the user, his ball number in the lottery is also displayed
(3) As soon as 3 tickets are sold, a draw can be started (Press 2) by selecting  in order to find 3 winning ball numbers.
(4) In order to declare winners corresponding the winning ball numbers (Press 3). This option cannot run untill and unless a draw has happened 
(5) Every time you select any of the above options, you are subjected back to the main menu

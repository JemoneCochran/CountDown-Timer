
## Countdown Timer

Users picks a time that will be the initial start time, in seconds, and the timer begins to countdown by intervals of 1 until it reaches 0, once the timer reaches 0, the code will print "DONE!!!"

## Authors

- [@Jemone Cochran II](https://www.github.com/octokatherine)


## Usage/Examples

#The method we need to access a timer, for counting up and down
import time

#The Local Variable needed that will be used to pick a starting time to count from,
#its set to zero as a default placeholder so the computer knows what variable you're referring to when giving input
#without declaring the variable i = 0, the program will not run as there is no placeholder to hold the variable in place

i = 0

#i is the variable that will take in a start time, it was declared before this step
 #in order for information to be collected and sent to the variable, the variable needs to already be created
 #the input method is used to take in user input by simply using the "input" function, this is needed for the program
 #to collect the appropriate information

i = input("Choose the start time: ")

#the for loop is used to state, in order from left to right, separated by commas
#"use the number from the input given to i, and countdown until you reach 0, countdown by increments of 1"

for i in range(int(i),0-1,-1):

    print(i)
#the time.sleep function is used to have the program stop its countdown for 1 second to give an accurate countdown
#that's what the sleep function means, the program "sleeps" for 1 second, we added "time" in front of it to make sure
#it was the variables in the "time" function only are being considered to sleep

    time.sleep(1)

#the if statement (called "if") used to ask the question "if the number inputted is at zero, print out to the screen,
#"DONE!!!" if the input is not at 0 yet, the if statement will not print anything

    if i == 0:
        print("DONE!")


## Acknowledgements

 -I Would like to acknowledge CodeAcademy https://www.codecademy.com/learn?g_acctid=243-039-7011&g_adgroupid=70946090375&g_adid=528849219079&g_adtype=search&g_campaign=account&g_campaignid=1955172604&g_ifcreative=&g_ifproduct=&g_keyword=codecademy&g_keywordid=kwd-41065460761&g_locinterest=&g_locphysical=9016939&g_merchantid=&g_network=g&g_partition=&g_placement=&g_productchannel=&g_productid=&g_source=%7Bsourceid%7D&gclid=Cj0KCQiAuqKqBhDxARIsAFZELmIxogq7SYuzHe0I637kX4UJ76VAJuqpo201X6SjXpQ7l6u-b8-jdaIaAticEALw_wcB&utm_campaign=US_Brand_Exact&utm_content=528849219079&utm_id=t_kwd-41065460761%3Aag_70946090375%3Acp_1955172604%3An_g%3Ad_c&utm_medium=paid-search&utm_source=google&utm_term=codecademy
 For the project idea as well as the information to create the project


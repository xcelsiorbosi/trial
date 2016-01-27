# trial
#name = input("what is your name?:")
#pet = input("what is your pets name?:")

#print("Aaron loves " + (name)+ " and " + (pet))


#favteam = input("what is your favourite hockey team?")
##change it to an upper to make it fluid for the user
#if favteam.upper() == "LALA" :
#    print("yeah go lala go")
#    print("thats great")
#print ("its okay if you prefer soccer")


#bestteam = crows
#favteam = input("what is your favourite hockey team?")
##change it to an upper to make it fluid for the user
#if favteam.upper() == bestteam.upper () :
#    print("yeah go lala go")
#    print("thats great")
#print ("its okay if you prefer soccer")







#calculations

##Declare and initialize the variables
#monthlyPayment = 0
#loanAmount = 0
#interestRate = 0
#numberOfPayments = 0
#loanDurationInYears = 0

##Ask the user for the values needed to calculate the monthly payments
#strLoanAmount = input("How much money will you borrow? ")
#strInterestRate = input("What is the interest rate on the loan? ")
#strLoanDurationInYears = input("How many years will it take you to pay off the loan? " )

##Convert the strings into floating numbers so we can use them in teh formula
#loanDurationInYears = float(strLoanDurationInYears)
#loanAmount = float(strLoanAmount)
#interestRate = float(strInterestRate)

##Since payments are once per month, number of payments is number of years for the loan * 12
#numberOfPayments = loanDurationInYears*12

##Calculate the monthly payment based on the formula
#monthlyPayment = loanAmount * interestRate * (1+ interestRate) * numberOfPayments \
#    / ((1 + interestRate) * numberOfPayments -1)

##provide the result to the user
#print("Your monthly payment will be " + str(monthlyPayment))

##Extra credit
#print("Your monthly payment will be $%.2f" % monthlyPayment) 







##this is a better way to convert to a float, way faster

#deposit = int(input("how much money do you want to deposit"))
#if deposit >= 100 :
#    print ("enjoy your toaster!")
#else:
#    print("well enjoy your paper towel")
#print("have a nice day")






## boolean variable
##should declare that freeToaster is false to begin with

#freeToaster = False
#deposit = int(input("how much money do you want to deposit"))
#if deposit > 100 :
#    freeToaster = True

#if freeToaster:
#    print ("enjoy ya toaster")
#print ("have a nice day!")
 







##complex if statements, order is very important, numbers start with the largest number

#country = input("where are you from").upper()
#if country == "CANADA":
#    print ("Hello")
#elif country == "AUSTRALIA" :
#    print ( "G'day")
#elif country == "USA" :
#    print("Hi")
#    #else catches any response we didnt anticipate
#else: 
#    print("Aloha, Ahoy, Bapidy boopidy")


# if and

#country = input("where are you from").upper()
#sport = input("whats your favourite sport").upper()

#if country == "AUSTRALIA" and sport == "FOOTBALL": 
#    print("oz oz oz, oi oi oi")
#if country == "CANADA":
#    print ("Hello")
#elif country == "AUSTRALIA" :
#    print ( "G'day")
#elif country == "USA" :
#    print("Hi")
#    #else catches any response we didnt anticipate
#else: 
#    print("Aloha, Ahoy, Bapidy boopidy")

    


#if or
#how can region be equal to two values... it cant
#will execute code if ant statement is true

#country = input("what is your region: ").upper()
#sport = (input("whats your fav sport: ")).upper()

#if country == "AUSTRALIA" or sport == "FOOTBALL": 
#    print("oz oz oz, oi oi oi. Sounds like we will get along")
#elif country == "AMERICA" or sport == "soccer":
#    print ( "I hope its all good there for you, but i dont like what you do")
#elif country == "USA" :
#    print("if no inputs are met except USA I print this line")
#    #else catches any response we didnt anticipate
#else: 
#    print("maybe fish in another hole? Bapidy! boopidy!")






#and or order do not want it to return positive if pet is correct
#country = input("what is your Country: ").upper()
#pet = (input("are you a dog or cat person: ").upper()

#if country == "AUSTRALIA" and \
#    pet == "DOG" or pet == "cat": 
##    print("well that sounds fantastic")


#sport = input("what is your sport: ").upper()
#team = input("what is your team : ").upper()

##can run the query this way
#sportIsFootball = False
#if sport == "FOOTBALL":
#    sportIsFootball = True

#teamIsCorrect = False
#if team == "PORT ADELAIDE" or team == "CROWS":
#    teamIsCorrect = True

#if sportIsFootball and teamIsCorrect:
#   print("great choices")


#can run the query this way
#if the sport is football and the teams are corws or port we ask if from adelaide

#if sport == "FOOTBALL" and (team == "CROWS" or team == "PORT ADELAIDE"):
#    print("are you from adelaide?: ")




#Nested if statements 5:51 zero to hero this is more about tabbing

#sport = input("what is your sport: ").upper()
#team = input("what is your team : ").upper()

#if sport == "FOOTBALL":
#    print("GO footy")
#    if team == "CROWS":
#        print ("good luck with a final")
#    print ("we do love foot ball")






#repeating events loops
#Have to indent the commands for the loop

#import turtle
#for steps in range(400):
#    turtle.forward(1)
#    turtle.right(1)
#for steps in range(400):
#    turtle.forward(1)
#    turtle.color("red")
#    turtle.left(1)


#    #nested loops
#import turtle
#for steps in range(5):
#    turtle.forward(100)
#    turtle.right(360/5)
#    for steps in range(4):
#        turtle.forward(50)
#        turtle.color("red")
#        turtle.left(360/4)
     

    #nested loops using variables
    #for steps in range (1,4) it will exe 3 times
    ##for steps in range (1, 10, 2) will cause it to jump by 2 until 10 
#import turtle
#nbrSides = 5
#for steps in range(5):
#    turtle.color("red")
#    turtle.forward(100)
#    turtle.right(360/nbrSides)
#    for steps in range(4):
#        turtle.color("red")
#        turtle.forward(50)
#        turtle.left(360/nbrSides)
#        print(steps)

#another way to do range of variables for loops
#for steps in [1,2,3,4,5]:
#for color in ['green', 'orange','blue','yellow', 'magenta']:
#for steps in range(5):          
#import turtle


#sides = int(input("how many sides would you like"))
#nbrSides = (sides)
#for colour in ['green', 'orange','blue','yellow', 'magenta']:
#    turtle.color(colour)
#    turtle.forward(100)
#    turtle.right(360/nbrSides)





#while means "do something while something is true"
#answer = "0"
#while answer != "42":
#    answer = input("what is the answer to the ultimate question of life?: ")
#print("congratulations you have the correct answer!!")

#counter starts at 0 in this example it will run 4 times (<= will run 5 times)

#import turtle
#counter = 0 
#while counter < 4:
#    turtle.forward(100)
#    turtle.right(90)
#    counter = counter+1
#    #counter +=1 is the same thing as above. this is the condition that ends the loop







##lists 7.25 (zero to hero)

#guests = ["Christopher", "Susan", "Bill", "Bill"] 

#print(guests[0])
#print(guests[1])
#scores = [32, 23, 52, 62 ]
#print(scores[3])
##can print backwards print there is no 0 unlike counting forwards: print(scores[-1])
##use this syntax for a loop that will read lists 
##square brackets are used to call an index variable
##guests = [] 
##scores = []

##Updating Lists
##guests[0] = steve
##guests.append = ('steve')
#guests.remove("Christopher")
#print(guests[0])
#print(guests[1])
##delete the first item in the list
#del guests[0]
#print(guests[0])
#print(guests[-1])
##append is used to add a value
#guests.append("Colin")
#guests.append("Martin")
##used to add a guest
##guests[3] = "Sonal"
#print(guests[-1])

##will remove the first value of this kind searched for
#guests.remove("Bill")
##using .index will return the position
#print(guests.index[-1])
##use a loop to remove all 0's


##option 1 for Using loop

#guests = ["Christopher", "Susan", "Bill", "Baza"] 
##print(guests[0])
##print(guests[1])
#scores = [32, 23, 52, 62 ]
#print(scores[3])
##we dont know how many values are in the list so we use len for "steps in range(4):"(replace 4 with opbject)
#cycle = len(guests)
#for steps in range(cycle):
#    print(guests[steps])

##option 2 for looping
##for loop is for every "value in the list" do "this"
#guests = ["Christopher", "Susan", "Bill", "Baza"] 
#for person in guests:
#    print(person)

##sort the names in alphabetical order
##guests.sort()



#test
# ask the user for the names of the guests (input)
#put those values into a list (make  list)
#sort the list (need a loop)while
#print the sorted list
#needs an if statement

#guests = []
#name = ""
#while name != "DONE":
#    name = input("what is your guests name, if no more guests type done?").upper()
#    guests.append(name)

#(guests).sort()
#cycle = len(guests)
#for guest in range(cycle) :
#        print(guests[guest])    
#name.remove ("DONE")
#print(guests[guest])
    


#if deposit >= 100 :
#    print ("enjoy your toaster!")
#else:
#    print("well enjoy your paper towel")





##8.03

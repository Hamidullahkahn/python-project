questions = [
    "What does CPU stand for",
    "What does GPU stand for",
    "What does RAM stand for",
    "What does PSU stand for",
    "What does PC stand for"
]

answers = [
    "Central Processing Unit",
    "Graphics Processing Unit",
    "Random Access Memory",
    "Power Supply",
    "Personal Computer"
]

totalScore = 0

# This function is welcoming you to my quiz game
def showInstructions():
    instructions = "Welcome to my quiz. Answers my questions. 1 to 5"
    print( instructions )

showInstructions()

answer = input( "Do you want to play?: y/n " )

if answer.lower() == "y":
    doYouWantToPlay = True
else:
    doYouWantToPlay = False

while doYouWantToPlay:
    for question in questions: # Looping through all questions
        currentIndex = 0
        userAnswer = input( f"{question}: " ) # The answer the user types

        # Checking to see if the user got it correct
        if userAnswer.lower() == str(answers[ currentIndex ]).lower():
            totalScore = totalScore + 1
        else:
             totalScore = totalScore + 0
        currentIndex = currentIndex + 1

    # After the loop. After all questions are displayed
    print( f"Your score is {totalScore}" )

    if totalScore >= 3: # you passed
        print( "You passed" )
    else: # You didn't pass
        answer = input( "Do you want to play again?: y/n " )
        if answer.lower() == "y":
            doYouWantToPlay = True
            currentIndex = 0
        else:
            doYouWantToPlay = False
            print( "Wait for my upcoming game. Not now. Later." )

# End of the program
print( "Good bye!!!!!!!!!!!!!!!!!!!!!!!!" )


# ReadME
#Assignment #1
print("Your assignments that combine to your final grade are: Weekly Assignments, Midterm, Final, and Quizzes.")
Assignment = input("How much for assignments? ")
print("Final Assignment Precentage: ", Assignment)
Midterm = input("How much for the midterm? ")
print("Final Midterm Precentage: ", Midterm)
Final = input("How much for the Final? ")
print("Final Final Exam Precentage: ", Final)
Quizzes = input("How much would you like for Quizzes? ")
print("Final Quizzes Precentage: ", Quizzes)

FinalP = (Quizzes + Final + Midterm + Assignment)
print("Final Percentage is ", FinalP, "%")

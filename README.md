# Testing-student-GPA1
# Name: Kevin Holt
# File: Lab.py
# Desc:
#	Receives input about a student then tests to see if they
#	made the Dean's List or the Honor Roll. Then continues
#	to loop, receiving more student info until "ZZZ" is
#	entered as the student's last name.

lName = input("Enter student's last name or ZZZ to quit: ")

while(lName != "ZZZ"):
	fName = input("Enter student's first name: ")
	gpa = float(input("Enter "+fName+" "+lName+"'s GPA: "))
	if(gpa >= 3.5):
		print(fName,lName,"has made it to the Dean's List!")
	elif(gpa >= 3.25):
		print(fName,lName,"has made it to the Honor Roll!")
	lName = input("Enter student's last name or ZZZ to quit: ")
print("End Program")

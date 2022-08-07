#Grading system for the school using CONDITIONS

while True:
   x=float(input('Enter your marks =  '))

   if x>=95:
      print("Grade is o+")
   elif x>=90:
      print("Grade is o")
   elif x>=85:
      print("Grade is A+")
   elif x>=80:
      print("Grade is A ")
   elif x>=70:
      print("Grade is B+")
   elif x>=60:
      print("Grade is B ")
   elif x>=50:
      print("Grade is c ")
   elif x>=40:
      print("Grade is D ")
   elif x>=33:
      print("Grade is E ")
   else:
      print("Sorry, you are fail")

   choice=input("Do you want to continue = y/n\n")
   if choice=='n':
       print("\n\nThank you for using the Grading system")
       break

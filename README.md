print("Title of program: Math revision program")
print()

counter = 0
score = 0
total_num_of_qn = 3


counter +=1
tracker = 0

while tracker !=1:
  
  print("Q"+str(counter)+") "+ "What is 12 + 2?")
  print("   a) 16")
  print("   b) 24")
  print("   c) 14")
  print("   d) 22")
  answer = input("Your answer: ")
  answer = answer.lower()
  if answer == "a":
    output = "Wrong."
    score -=1
  elif answer == "b":
    output = "Wrong. "
    score -=1
  elif answer == "c":
    output = "Yes, that's right!"
    tracker =1
    score +=1
  elif answer == "d":
    output = "Wrong. "
    score -=1
  else:
    output = "Please choose a, b, c or d only."
  
  print()
  print(output)
  print()
  print("Your current score: " + str(round((score/total_num_of_qn*100),1)) + "%"  )
  print()
  print()
  


counter +=1
tracker = 0

while tracker !=1:
  
  print("Q"+str(counter)+") "+ "What is 3x7?")
  print("   a) 21")
  print("   b) 23")
  print("   c) 10")
  print("   d) 19")
  answer = input("Your answer: ")
  answer = answer.lower()
  if answer == "a":
    output = "Yes, that's right!"
    tracker =1
    score +=1
  elif answer == "b":
    output = "Wrong."
    score -=1
  elif answer == "c":
    output = "Wrong."
    score -=1
    
  elif answer == "d":
    output = "Wrong. "
    score -=1
  else:
    output = "Please choose a, b, c or d only."

  print()
  print(output)
  print()
  print("Your current score: " + str(round((score/total_num_of_qn*100),1)) + "%"  )
  print()
  print()
  
  

counter +=1
tracker = 0

while tracker !=1:
  
  print("Q"+str(counter)+") "+ "What is 24-19?")
  print("   a) 4")
  print("   b) 7")
  print("   c) 8")
  print("   d) 5")
  answer = input("Your answer: ")
  answer = answer.lower()
  if answer == "a":
    output = "Wrong. "
    score -=1
  elif answer == "b":
    output = "Wrong.  "
    score -=1
  elif answer == "c":
    output = "Wrong.  "
    score -=1
    
  elif answer == "d":
    output = "Yes, that's right!"
    tracker =1
    score +=1
  else:
    output = "Please choose a, b, c or d only."

  

  print()
  print(output.lower())
  print()
  print("Your current score: " + str(round((score/total_num_of_qn*100),1)) + "%"  )
  print()
  print()
  
print("End of quiz!")
  

# BMI-Calculator-

print ("BMI CALCULATOR📱")
print("                              ")

height = int(input("Enter your height (Cm):"))
print("                              ")
weight = int(input("Enter your Weight (Kg):"))
print("                              ")

height = height/100
height = height*height

bmi = weight/height

print("Your BMI :", bmi)

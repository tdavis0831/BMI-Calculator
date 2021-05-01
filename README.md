# BMI-Calculator
#Calculates BMI using kg and m
weight=int(input("What is your weight in kg?:"))
height=float(input("What is your height in m?"))
bmi= weight/(height*height)
bmi_int=int(bmi)

print(bmi_int)

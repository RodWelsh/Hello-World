# Hello-World
Just another IT student starting the journey.
Did my first python PRogram today for a BMI calculator. I've always beena bit of a gym guy and like a laugh, check out my code and give me some tips, tricks, or challenges to improve. - peace Rod
print ("Lets work out your BMI")
name = input ("What is your name?")
print ("Great thanks for the information {}".format (name))
weight = input ("What's your weight")
height = input ("What's your height?")
bmi = float(weight) / (float(height) * float(height))
print (bmi)
if bmi < 20 :
    print ("Time to eat some chicken fella")
elif bmi > 20 and bmi < 25 :
    print ("Maybe hit some carbs fella")
elif bmi > 25 and bmi < 30 :
    print ("Right in the sweet spot fella")
else :
    print ("Woah fella time to shred")

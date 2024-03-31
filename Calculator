import random

#Greetings
print("Welcome to Ora Lobo Resturant")

#Generate the customers bill
bill = random.randint(100,300)

#Tell the cutomer thier total bill
print(f"Your total bill is ${bill}")

#Generat the tip amount
tip_decision = input("Will you be paying tips? yes/no")

if tip_decision == "yes":
    percent_cash = input("Will you be paying a specic amount or percent? amount/percent")
    if percent_cash == "percent":
        percent_tip = int(input("How many percent?"))
        total_tip = percent_tip/100 * bill
        total_bill = bill + total_tip
    else:
        amount_tip = int(input("What is your tip amount?"))
        total_bill = bill + amount_tip
else:
    print(f"Your total bill is ${bill}")

#How are they paying
paying = input("How are you guys paying, seperate or single?")

if paying == "seperate":
    total_pay_guest = int(input("How many guest are paying?"))
    bill_per_guest = total_bill/total_pay_guest
    print(f"Total bill per guest is ${round(bill_per_guest,2)} to be shared amoungst {total_pay_guest} guests.\nThank you for visiting Ora Lobo!")
else:
    print(f"Your total bill is ${round(total_bill,2)}\nThank you for visiting Ora Lobo!")

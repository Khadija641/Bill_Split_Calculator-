# Bill_Split_Calculator-
"A simple Python script to split bills among friends."

print("-----------------------------------------")
print("-----------------------------------------")
print("        💰💸 Bill Split Calculator 💰💸")
print("-----------------------------------------")
print("-----------------------------------------")
total_bill = int(input("Enter amount of bill: Rs "))
friends = int(input("Enter no. of friends: "))
if friends <= 0: 
    print("Number of friends must be greater then zero")
else:
    print("------Tip option-------")
tip = int(input("If you want,Enter amount of tip: Rs"))
if tip <= 0:
    print("No tip added ")
    each_pay = float(total_bill/friends)
else: 
    Bill_tip = total_bill + tip 
    each_pay = float(Bill_tip / friends) 
print("---------Reciept Summary--------") 
print(f"    💸Amount of bill💸 : Rs {total_bill} ") 
print(f"    ✨Tip added✨ : Rs {tip} ") 
print(f"    🥰No. of friends🥰 : {friends} ") 
print(f"    💵Each person pays💵 : Rs {each_pay} ") 
print("----------------------------------------")
print("----------------------------------------")
print("      Thank you for using me 😊")
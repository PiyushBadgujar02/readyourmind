import time
print("Starting the game.....")
time.sleep(1)
print("\nyou have to take a number in your mind in range of 1 to 63")
print("\ninitializing the programe.....\n")
time.sleep(2)
lis1=[1,3,5,7,9,11,13,
      15,17,19,21,23,25,
      27,29,31,33,35,37,
      39,41,43,45,47,49,
      51,53,55,57,59,61,63]

lis2=[2,3,6,7,10,11,14,15,18,19,22,23,26,27,30,31,34,35,38,39,42,43,46,47,50,51,54,55,58,59,62,63]
lis3=[4,5,6,7,12,13,14,15,20,21,22,23,28,29,30,31,36,37,38,39,44,45,46,47,52,53,54,55,60,61,62,63]
lis4=[8,9,10,11,12,13,14,15,24,25,26,27,28,29,30,31,40,41,42,43,44,45,46,47,56,57,58,59,60,61,62,63]
lis5=[16,17,18,19,20,21,22,23,24,25,26,27,28,29,30,31,48,49,50,51,52,53,54,55,56,57,58,59,60,61,62,63]
lis6=[32,33,34,35,36,37,38,39,40,41,42,43,44,45,46,47,48,49,50,51,52,53,54,55,56,57,58,59,60,61,62,63]
print(lis1)
input_user_for_lis1=input("is your number is in above list:(ans should be in yes or no):\n")
a=0
if input_user_for_lis1=="yes":
    a=a+1
else:
    pass
print(lis2)
input_user_for_lis2=input("is your number is in above list:(ans should be in yes or no):\n")
if input_user_for_lis2=="yes":
    a=a+2
else:
    pass
print(lis3)
input_user_for_lis3=input("is your number is in above list:(ans should be in yes or no):\n")
if input_user_for_lis3=="yes":
    a=a+4
else:
    pass
print(lis4)
input_user_for_lis4=input("is your number is in above list:(ans should be in yes or no):\n")
if input_user_for_lis4=="yes":
    a=a+8
else:
    pass
print(lis5)
input_user_for_lis5=input("is your number is in above list:(ans should be in yes or no):\n")
if input_user_for_lis5=="yes":
    a=a+16
else:
    pass
print(lis6)
input_user_for_lis6=input("is your number is in above list:(ans should be in yes or no):\n")
if input_user_for_lis6=="yes":
    a=a+32
else:
    pass

print(f"let me read your mind\n")

time.sleep(5)
print("and the number in your mind is\n")
time.sleep(2)
print(f"your number in your mind is {a}\n")
print("m i an genious what do you think")

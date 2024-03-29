# Fizz-Buzz
for number in [1,2,3,4,5]:
    print(number)
  
for number in range(1, 101): 
    if ((number % 3) == 0) and ((number % 5) == 0): 
        print("Fizz Buzz")
    elif ((number % 3) == 0):
        print("Fizz")
    elif ((number % 5) == 0):
        print("Buzz")
    else: print (number)

vthreshold = 10
v = 0
while (v < vthreshold):
    v = v + 1
print (v)

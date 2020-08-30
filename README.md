# Python-Program-to-check-Armstrong-Number
num = int(input("Enter a number: "))
#length of the string
l= len(str(num))
# initialize sum with 0
s = 0
# find the sum of the cube of each digit
t = num
while t > 0:
   d = t % 10
   s=s+(d**l)
   
   t=t//10
   
if num == s:
   print(num,"is an Armstrong number")
else:
   print(num,"is not an Armstrong number")


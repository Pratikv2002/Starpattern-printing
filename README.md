# Starpattern-printing
      Star pattern
          *
         ***
        *****
       ******* 
         
a = int(input("Enter number:"))
b = a / 2
b = int(b)
for i in range(1,a,2):
    print("   "," "*b,"*" * i)
    b=b-1

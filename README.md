# fibonacci 
x = int(input("enetr your digit: "))

n1,n2 = 0,1
y = 0

if x<=0:
    print("pls enter positive interger!!")
elif x==1:
    print("fibonacci number number: ")
    print(n1)
else:
    print("fibonacci number: ")
    while y<x:
        print(n1)
        nth = n1+n2
        n1 = n2
        n2 = nth

        y+=1




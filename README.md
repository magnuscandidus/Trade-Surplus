# Trade-Surplus
for i in range (int(input())):
    a1,a2,b1,b2 = map(int,input().split())
    x = a1-a2
    y = b1-b2
    z = x+y
    if((-z)<=0):
        print("No")
    else:
        print("Yes")

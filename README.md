# feb-22-ass-2
Assignment-2
n = int(input("Enter the Number"))
for i in range(1,n+1):
    for j in range(1,i):
        print(j,end="  ")
    print("\n")
for i in range(2,n):
    for j in range(n,i,-1):
        print(n-j+1,end="  ")
    print("\n")

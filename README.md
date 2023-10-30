# first
n,m = map(int,input().split())
d=[]
if n>m:
    for i in range(1,m+1):
        if n%i==0 and m%i==0:
            d.append(i)
else:
    for i in range(1,n+1):
        if n%i==0 and m%i==0:
            d.append(i)

print(len(d))

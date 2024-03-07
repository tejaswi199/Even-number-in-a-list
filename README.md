#Approach-1
n=int(input())
a=list(map(int,input().split()))
x=[]
for i in range(n):
  if a[i]%2==0:
    x.append(a[i])
print(x)

#Approach-2
n=int(input())
a=list(map(int,input().split()))
print
x=[]
m=0
for i in a:
  if i%2==0:
    x.append(i)
print(x)

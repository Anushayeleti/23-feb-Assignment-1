l=[]
n=int(input('enter number:'))
for i in range(n):
    e=int(input('enter number:'))
    l.append(e)
max=l[0]
for i in range(1,n):
    if l[i]>max:
       max=l[i]
print('max',max)
min=[0]
for i in range(1,n):
    if l[i]<min:
       min=l[i]
print('min',min)

Output:enter number:5
       enter number:9
       enter number:3
       enter number:7
       enter number:1
       enter number:8
       max 9

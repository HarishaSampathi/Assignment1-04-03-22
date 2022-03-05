# Assignment1-04-03-22
Write a program to count the duplicate elements in the list
l=[]
n=int(input())
for i in range(n):
    x=int(input())
    l.append(x)
print(l)
res=[]
for i in l:
    if l.count(i)>1: 
        if i not in res:
          res.append(i)
print(i)
output:
10
26
4
5
6
6
5
0
4
41
41
[26, 4, 5, 6, 6, 5, 0, 4, 41, 41]

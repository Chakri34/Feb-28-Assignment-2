x=[1,2,3,2,3,4,5,6,5,6,]
l=[]
for i in x:
    if i not in l:
        if x.count(i)==1:
            l.append(i)
print(l)

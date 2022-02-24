# seperate-odd-and-even-numbers-from-list
x=int(input("enter a value: ")) 

x=input("enter a value:") 

l=x.split() 

n=len(l) 

o=[ ] 

e=[ ] 

for i in range(n):       
j=i+1       
if j%2==0:            
  e.append(l[i])       
else:             
 o.append(l[i]) 

print(o,e)

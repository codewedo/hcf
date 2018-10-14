# hcf
print("ENTER TWO NUMBERS WHOSE HCF TO BE FIND")
n1=int(input())
n2=int(input())

list=[]
if(n1<n2): #if n2 is greater than n1 than this condition is true
   for i in range(1,n1+1):
     if n1%i==0 and n2%i==0:
        
        list.append(i)
     else:
        continue

else:  #if n1 is greater than n2 than this condition is true
   for i in range(1,n2+1):
     if n1%i==0 and n2%i==0:
        
        list.append(i)
     else:
        continue
print("HCF OF",n1,"AND",n2,"IS" ,max(list))
#max(list) prints the max value of list.

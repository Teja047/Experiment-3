# Experiment-3

mylist = []
n = int(input("Enter any number:"))
for x in range(n):
    num = int(input("Enter a number:"))
    mylist.append(num)
print("My updated list is:",mylist)




l = [10,20,30,"sana",(10+20j),True,"l"]
print(l[3])
print(l[-2])
print(l[1:4])
print(l)
l.remove(30)
print(l)




l = [10,20,30,40,60,True,]
print(len(l))
print(l)
print (max(l))
print (min(l))




mylist = [8,2,3,0,7]
sum = 0
for i in mylist:
    sum = sum+i
print("The sum is:",sum)




s = input("Enter the string:")
print(s.split())





n = int(input("Enter the value of n:"))
mylist = []
for i in range(n):
    num = int(input("Enter a number:"))
    mylist.append(num)
print("Even numbers are:")
print("[",end=' ')
for num in mylist:
    if num%2 == 0:
        print(num,end=',')
print("]")





list = [10,20,30,'sai',True,0,(10+20j),False,'l',True]
print(list)
x = list.copy()
print(x)
list.pop(3)
print(list)
del list[2]
print(list)
list.reverse()
print(list)
list.clear()
print(list)

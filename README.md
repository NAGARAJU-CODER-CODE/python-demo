# Python data types

1)list  method
2)tuple method 
3)set   method
#It just Normal program in python
print("hello world")


if True:
    print("this is true")
    print("hello Naga ")
else:
    print("this is false")  
    print("hello user")

1)	List method 
2)	Tuple methods
3)	Set methods

a=True
b=False
if a:
    print("this is true block a")
    print("hello Naga ")    
else:
    print("this is false block a")  
    print("hello user" )  

if b:
    print("this is true block b")
    print("hello Naga ")        
else:
    print("this is false block b")  
    print("hello user" )  




	
a=True
if a:
    print("hi")
    

a=0
a

a=5
a=a+1
a


if True and True and True or False:
    print("complex condition is true")
    


if True and True and True and False:
    print(" complex condition is True")
else:
    print("complex condition is False")

fruits = ["apple", "banana", "cherry"]
for x in fruits:
  print(x)

fruits = ["apple", "banana", "cherry"]
for x in fruits:
  print(x)
  if x == "cherry":
    break

number=int(input("Enter a number: "))
print("You entered number is:",number)
if number!=0:
    if number%2==0:
        print("even")
    else:
        print("odd",number)
    
else:
    print("neutral")



rain=1#True
if rain==False:#True
    print("it is raining ")
else:
    print("it's not raining")

a=7
b=5
var1=int(input("enter your number b/w 1 to 3"))
print(f"your entered:",{var1})
if var1==1:
    print(a+b)
elif var1==2:
    print(a-b)
elif var1==3:
    print(a*b)
else:
    print("your number not b/w 1 to 3.")

 
a=10
b=2
c=5
if a>b and a>c:
    print("a is largest")
    if a>b and a<c:
        print("a is in middle")
    elif a<c and a<b:
        print("c is minmum")
elif b>c and b>a: 
    print("b is largest")
    if b>a and b<c:
        print("b is in minmum")
    else:
        print("b is middle")
elif c>a and c>b:
    print("c is largest")

a =int(input("enter your lucky number b/w 1 to 21")) #this is used for number b/w your entered values
print("your entered number is:",a) #this is your value
if a and a<=5: #this your condition b/w the numbers
    print("try again ") #print the statement
elif a==6: #this is no output option
    print("6 has no output") # no option result
elif a and a<=10: # this is another condition b/w 7 to 10
    print("better") 
elif a and a==11:
    print("better luck next time")
elif a and a<=15:
    print("good luck")
elif a and a<=21:
    print("nice day")
else:
    print("out off number ")



a=25
b=43
c=13
if a>b and a>c:
    print("a is maximum")
    if b<c:
        print("c is middle")
        print("b ismin") 
    else:
        print("b is middle")
        print("c is min")
        
elif a<b and c<b:
    print("b is maximum")
    if a<c:
        print("c is middle")
        print("a is min")
    else:
        print("a is middle")
        print("c is min") 

elif a<c and b<c:
    print(" c is max")
    if a<b:
        print("b is middle")
        print("a is min")
    else:
        print("a is middle ")
        print("b is min")
    


x =int(input("enter your current bill units"))
print("your entered units is:",x)
bill=0
if x>=0 and x<=100:
    print("no charge",bill)
elif x>=100 and x<200:
    bill=100*0 +(x-100)*2
elif x>=200 and x<400:
    bill=(100*0)+(200-100)*2+(x-200)*3
elif x>=400 and x<500:
    bill=(100*0)+(200-100)*2+(400-200)*3+(x-400)*5
elif x>=500:
    bill=(100*0)+(200-100)*2+(400-200)*3+(500-400)*5+(x-500)*7
    
print("charge is units in total")
print(bill)
 



def my_function():
    print("Hello, world ")
my_function()



 
a=2
b=10
i=1
while i<=b:
    print(a,"*",i,"=",a*i)
    
    i=i+1


a=0
b=10
while a<=b:
    print("helo nagaraju",a)
    a=a+1
    

user_name=input("enter your name")
password=input("enter your password")
a=True
if user_name=="admin" and password=="1234":
    while a:
        if password=="1234":
            print("welcome admin")
            print("try again")
            a=False
                    
elif user_name!="admin" or password=="1234":
    print("invalid user")
elif user_name=="admin" and password!="1234":
    print("invalid password")



a=0
b=10
y=0
while a<=b:
    y=y+a
    a=a+1
print(y)

num=int(input("enter your num"))
option=input("enter your option ")
a=1
b=10
y=1
if option=="add":
    while a<=b:
        y=y+a
        a=a+1
else:
    while a<=b:
        y=y+a
        a=a+1

print(y)


ALL List method in python
#1.append method --> to add an item to the end of the list
f=["hi","hello","go","out"]
f.append("good morning every one")
print(f)
print()

#2.clear method
fn=[1,2,3,4,5,6,7,8]
fn.clear()
print(fn)
print()

#3.copy method
fn1=[1,2,3,4,5,6,7,7]
fn2=fn1.copy() 
print(fn2)
print()

#this is another option to copy the file
fn2 = list(fn1)
print(fn2)
print()

# copy the slice operation  like this ->
fn1 =fn2[:]
print(fn1)
print()





#4.count method 
fn=["hi","hell","hi","hello","hi"]
n=fn.count("hi")
print(n)


#5.extend method 
f.extend(fn1) #this is used for copy the one file to another file using list data sets
print(f)
print()

#6.index method 
print(f[4]) #direct accessing the index value
print(f[1:5]) #it is accessing 1 index to 4 index(n-1 fromation) -> printing 4 values
print()

#7.pop method 
a=["a","b","c","d","f"]
a.pop()
print(a) # this is used for pop the last element in the list items 
a.pop(3) #this is used for specific index value is popped in the list
print(a)
a.pop(1) #this is used for direct printing value without print fuction() ->it will showing which value is popped 




#8.remove method 
b=[1,3,4,5,6,7,7,8,9,8,10]
b.remove(1) # only value, not index nnumber
print(b)
b.remove(8) #this used for first index value is removed 
print(b) # there are two same value but it removes first value.
print()

#9.reverse method
b.reverse()
print(b)
print()

#10.sort method 
b.sort()  #this is acsceding order
print(b)
print()
c=[2,3,42,42,65,62,74,57,46,35]
c.sort(reverse=True) #this is descending order
print(c)





#11.change list items:
list1=['hi',"hlo","good","bad","execlent","clear","delete"]
list1[1]="nice"
print(list1)
list1[1:5]=["a","b","c","d"]
print(list1)
list1[1:4]=["a","b","c","v"]
print(list1)
print(len(list1))
# note: --> the length of the list will change when the number of items does not match the number of items replaced





# 12.insert method --> In this method passing two arguments one index value another one real value 
c=[2,3,4,5,6,7,8,9] #this is used for specific index value replace method
c.insert(1,45)
print(c)
c.insert(5,12) #It is not replace method, insert new value 
print(c)





#14.del method 
d=[2,3,4,5,6,7,8,9]
del d[1]#index position 
print(d)
print()
del d #---> It is also used for complete delete the list items 
print("this show u d is not defined")


#list item -data types
li1=["apple","banana", "chery","yes"]
li2=[1,2,3,45,5]
li3=[True, False,True,False,True]
li4=[1,2,4,"apple","banana",True,False ]
print(type(li1))


#Using the list() constructor to make a List:
my_list=list()

print(my[1])
print(my[-1])
print(li4[1:4])
print(li4[2:])
print(li4[-4:-1])
print(li4[-4:])

#change the list items 
li1[1]=23
print(li1)
li2[1:3]=["a","b"]
print(li2)
li=[1,3,5]
li[1:4]=["a"]
print(li)
print(len(li))






#To insert a new list item, without replacing any of the existing values, we can use the insert() method.
li=[1,3,5]
li.insert(2, "kiwi")
print(li)
#append method 
k=["f","g","h","b"]
print(k)
k.append("this")
print(k)
#extend() methed 
f=["apple","banana","cherry"]
m=["mn","vb","bh","ng"]
print(f)
f.extend(m)
print(f)


#remove the items form the list
#remove() method
li=["apple","banana","cherry"]
print(li)
li.remove("banana")
print(li)
#pop() method. it is used for remove specified index
#If you do not specify the index, the pop() method removes the last item.
li1=["app","iocn","cherry","bi","mmm","nnn"]
print(li1)
li1.pop(1)
li1.pop(2)
print(li1)
#def keword used for removes the specified index 
thislist = ["apple", "banana", "cherry"]
print(thislist)
del thislist[0]
print(thislist)

#Clear(). this is method empties the list
#that used for the list still remains, but it has no content
thislist.clear()
print(thislist)

# loop are used in list method 
t=["ff","00","ffgg","mfkmm","kmjkm"]
for i in t:
    print(i)

#print all items by referring to their index number: and using range method and len method
t=["ff","00","ffgg","mfkmm","kmjkm"]
for i in range(len(t)):
    print([i])
    
    

#using while loop in the list
#print all items by referring to their index number: and using range method and len method
t=["ff","00","ffgg","mfkmm","kmjkm"]
i=0
while i<len(t):
    print(i)
    print([i])
    i=i+1
    

#looping using list Comprehension
t=["ff","00","ffgg","mfkmm","kmjkm"]
[print(x) for x in t]

import sys

print(sys.version)


#list comprehension
#it is used for based list into new list 
#without list comprehension you will have to write a for statement with a condition test inside 
fruits =["apple","banana","cherry","kiwi","mango"]
newlist=[] #this used for name of letter(like "a" ,"any letter") in the list it will print outside output
for i in fruits:
    if "a" in i:
        newlist.append(i)
        
print(newlist)

#this code used for single line of code 
fruits =["apple","babana","cherry","mango","orange"]
newlist1=[i for i in fruits if "a" in i] # with no if statement (newlist =[x for x in fruits ])

print(newlist1)#this code is above code using single line code 

# syntax for single line code 
#newlist = [expression for item in iterable if condition == True]
#another code is here 
fruits =["apple","babana","cherry","mango","orange"]
newlist1=[var for var in fruits if "a" in var]
print(newlist1)



#Iterable 
#the iterable can be any iterable object, like a list ,tuple ,set ete.
#range function 
newlist=[x for x in range(10)]
print(newlist)

#same example , but with a codition:
#accept only numbers lower than 5:
newlist=[x for x in range(10) if  x < 5]
print(newlist)

newlist=[x.upper() for x in fruits]
print(newlist)

#set all values in the new list to "hello":
newlist =['hello' for i in fruits] #this is used for every number changed into a hello word 
print(newlist)








#The expression can also contain conditions, not like a filter, but as a way to manipulate the outcome:
#return "orange" instead of "banana":
fruits =["apple","banana","cherry","kiwi","mango"]
newlist=[i if i != "banana" else "orange" for i in fruits]
print(newlist)

 









ALL TUPLES methods in python
#tuple is ordered ,unchangeable ,allow duplicate values 


#count method
a=(1,2,3,4,5,2,2,2)

print(a.count(2)) #this is count the value for the tuple

#2.index method
b=(1,2,3,45,654,65,3,3,543,3,4)
print(b[4])


# the tuple() constructuctor
fn=tuple(("apple","banana","cherry")) # note --> the tupleround-brackets
print(fn)


# the tuple() constructuctor
fn=tuple(("apple","banana","cherry")) # note --> the tupleround-brackets
print(fn)


#3. del() method 
fn1=tuple(("apple","banana","cherry"))
del fn1
print(fn1)



#unpacking a tuple:
#---> assign values to it. this it is called "unpacking ":
#---> we are also allowed to extract the values back into variable. This is called "unpacking ":
fruits=("apple","banana","cherry")
(green,yello,red)=fruits
print(green)
print(red)
print(yello)
print()
# note --> the number of variable must match the number of values in the tuple, If not, you must use an asterisk to collect the remaining values as list
f=("apple","banana","cherry")
(n,*m)=f
print(n)
print(m)


#loop through a tuple
tuple1=("apple","banana","cherry","kiwi")
for i in tuple1:
    print(i)
    


#loop thrugh the index numbers 
#use the range().and len(). functions to create a suitable iterable.
for i in range(len(tuple1)):
    print(tuple1[i])
    





#using a while loop
#use the len(). function to determine the length of the tuple 
i=0;
while i<len(tuple1):
    print(tuple1[i])
    i=i+1
    

# join two tuples
tuple1=('a','b','c','d','e')
tuple2=(1,2,3,4)
tuple3=tuple1 + tuple2
print(tuple3)


#multiply tuples --> multiply the fruits tuple by 2:
fruits=("apple","banana","cherry","kiwi")
mytuple = fruits * 2
print(mytuple)
print()

#Duplicates not allowed 
set1={'apple',"apple",'banana',"cherry"}

#Duplicates not allowed 
set1={'apple',"apple",'banana',"cherry"}
print(set1)
#note --> the values True and 1 are considered the same value in sets, and are treated as duplication 
#note --> the values False and 1 are considered the same value in sets, and are treated as duplication 


ALL METHODS  in python
#A set is a collection which is unordered , unchangeable*, and unindexed.
#note -->Set items are unchangeable, but you can remove items and add new items
#sets are written with curly brackets.
#Once a set is create ,you cannot change its items, but you can remove items and add new items.

#Note: The values True and 1 are considered the same value in sets, and are treated as duplicates:
#Note: The values False and 0 are considered the same value in sets, and are treated as duplicates:

set1={"apple","banana","kiwi","cherry"}
print(set1)
#Sets are unordered, so you cannot be sure in which order the items will appear.




#set items - Datatypes 
set1 = {"apple","banana","cherry"}
set2 = {1,2,5,6,7,9}
set3 = {True,False , False}
set4={"abc",34,True,49,"male"}
print(set4)
print(set1,set2,set3)

# the set constrructor 
set1=set(("apple","banana","cherry")) #note the double round- brackets
print(set1)

#access set items using loop statements
set1={"apple","banana","cherry"}

for i in set1:
    print(i)
    
print()
print(set1)
print("banana" in set1)
print()
print("cherry" not in set1)
#Once a set is created, you cannot change its items, but you can add new items.

#Add items in sets
#1.add method
set1.add("orange")
print(set1)

#2.update() method 
set1={"apple","banana","cherry"}
set2={"kiwi","mango "}
set1.update(set2)
print(set1)

#add any iterable
#the object in the update(). method does not have to be a set, it can be any iterable object(tuples,lists,dictionaries,etc.)
Set1={"apple","banana","cherry"}
mylist=["kiwi","orange"]
set1.update(mylist)
print(set1)

#remove items
set1={"apple","banana","cherry"}
set1.remove("banana")
print(set1)
print()
set1.remove("cherry")
print(set1)
print()

#discard() method ---> note -> if the item to remove does not exist, discard(.). will Not raise an error.
set1={"apple","cherry","banana"}
x= set1.pop()#x=set1.remove("apple")   
print(x)     #print(x)
print(set1)
#Sets are unordered,So when using the pop(.). method ,you do not konw which item that gets remove

#clear(). method 
set1={"apple","banana","cherry"}
set1.clear() #The clear() method empties the set:-->empty the set 
print(set1)

#del method 
set1={"a","b","c","d","e","string"}
del set1
print(set1) #It will thor a error is set1 is not defined

Output:
set()
---------------------------------------------------------------------------
NameError                                 Traceback (most recent call last)
Cell In[9], line 9
      7 set1={"a","b","c","d","e","string"}
      8 del set1
----> 9 print(set1)

NameError: name 'set1' is not defined

#using for loops in set operation 
set1={"apple","banana","cherry"}
for i in set1:
    print(i)


#join sets
#There are several waus to join two or more sets in python.
#1.The union(.). and update(.). method joins all items from both sets.
#2.The intersection(.). method keeps ONLY the duplicates.
#3.The difference (.). method keeps the items from the first set that are not in the other set(s).
#4.symmertic difference(.). method keep all items EXCEPT the duplication.

#1.union() method -> return a new set with all items from both sets.
set1={'a','b','c'}
set2={1,2,3,4}
set3=set1.union(set2)
print(set3) 
print()
# You can use the | operator instead of the union() method, and you will get the same result.
set4=set1 | set2
print(set4)
set5={True,False,True,0}
set6=set1.union(set2,set3,set5)
print(set6)
print()
#another option is | opreation with multiple time you have to used 
set7=set1 | set2 | set3 |set4 | set5
print(set7)
print()

#join a set and a tuple 
#The union(). method allows you join a set with other data types, like lists or tuples.
x={'A','B','C','D'}
y=(1,2,3,4,5,6,7,8)
z=x.union(y) #Note: The  | operator only allows you to join sets with sets, and not with other data types like you can with the  union() method.
print(z)


#update(). method
#The update(). method changges the original set, and does not return a new set.
set1={'a','b','c','d'}
set2={1,2,3}
set1.update(set2)
print(set1)
print()

#intersection method
#The intersection() method will return a new set, that only contains the items that are present in both sets.
set1={"apple","banana","cherry"}
set2={"apple","microsoft","google "}
set3=set1.intersection(set2)
print(set3) 
print()

#Note: The & operator only allows you to join sets with sets, and not with other data types like you can with the intersection() method.

#The intersection_update() method will also keep ONLY the duplicates, but it will change the original set instead of returning a new set.
set1 = {"apple", "banana", "cherry"}
set2 = {"google", "microsoft", "apple"}

set1.intersection_update(set2)

print(set1)


#The difference() method will return a new set that will contain only the items from the first set that are not present in the other set.
set1 = {"apple", "banana", "cherry"}
set2 = {"google", "microsoft", "apple"}

set3 = set1.difference(set2) #same as--> set3 = set1 - set2

print(set3)
print()
# You can use the - operator instead of the difference() method, and you will get the same result.
# Note: The - operator only allows you to join sets with sets, and not with other data types like you can with the difference() method.

#difference_update()
#Use the difference_update() method to keep only the items from the first set that are not present in the other set:
set1 = {"apple", "banana", "cherry"}
set2 = {"google", "microsoft", "apple"}

set1.difference_update(set2)

print(set1)



#symmetric_difference() 
#The symmetric_difference() method will keep only the elements that are NOT present in both sets.
set1 = {"apple", "banana", "cherry"}
set2 = {"google", "microsoft", "apple"}

set3 = set1.symmetric_difference(set2)

print(set3)
print()
#You can use the ^ operator instead of the symmetric_difference() method, and you will get the same result.
#Note: The ^ operator only allows you to join sets with sets, and not with other data types like you can with the symmetric_difference() method.

set1 = {"apple", "banana", "cherry"}
set2 = {"google", "microsoft", "apple"}

set3 = set1 ^ set2
print(set3)


#frozenset
#frozenset is an immutable version of a set.
#Unlike sets, elements cannot be added or removed from a frozenset.

#use the frozenset() constructor to create a frozenset from any iterable.

x=frozenset({"apple","banana","cherry"})
print(x)
print(type(x))

#The symmetric_difference_update() method will also keep all but the duplicates, but it will change the original set instead of returning a new set.

#Use the symmetric_difference_update() method to keep the items that are not present in both sets:
set1 = {"apple", "banana", "cherry"}
set2 = {"google", "microsoft", "apple"}

set1.symmetric_difference_update(set2)

print(set1)
print()


#Method Shortcut           Description

#copy()                                ->Returns a shallow 
#difference()            -             ->Returns a new frozenset with the difference    
#intersection()          &             ->Returns a new frozenset with the intersection  
#isdisjoint()                          ->Returns whether two frozensets have an intersection    
#issubset()             <= / <         ->Returns True if this frozenset is a (proper) subset of another 
#issuperset()           >= / >         ->Returns True if this frozenset is a (proper) superset of another   
#symmetric_difference()   ^            ->Returns a new frozenset with the symmetric differences 
#union()                  |            ->Returns a new frozenset containing the union   




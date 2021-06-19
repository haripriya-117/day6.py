# day6.py
day6.py
#write a python script to merge two python dictionaries
dict1={'raj':40,'harry':60,'gina':50}
dict2={'mano':30,'ramu':20,'eika':10}
print(dict2.update(dict1))
print(dict2)

#write pyton program to remove key from a dictionary

del dict1['raj']
print(dict1)
dict2.pop('mano')

dict2.popitem()
print(dict2)

#write python program to map two lists into dictionary
d1=['A','F','U','B']
d2=[3,5,6,8]
res={}
for key in d1:
    for value in d2:
        res[key]=valued2.remove(value)
        break
print("Dictionary is",str(res))

#write a pyton program to find lenght of list

name={'S','I','P','T'}
print("number of names in set is :",len(name))
name1={'hary','githha','joikia','diiona'}
name2={'riod','kala','lala','rai'}
name1.update(name2)
print("adding two sets:",name1)
name1.add("teddy")
print(name)

name.remove("yoyo")
print(name1)

#python program to remove the intersection of a 2nd set from the 1st one

a1={30,40,60,50,10,90}
a2={30,60,40,10,20,70}
print(a1.intersection(a2))

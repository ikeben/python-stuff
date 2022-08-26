from audioop import reverse
from cgi import print_arguments
from itertools import count
from operator import countOf
from pickle import POP_MARK, PicklingError
from termios import HUPCL
from time import time
from xml.sax.handler import property_interning_dict


messsage="hello python crash course"
print(messsage.upper())
print(messsage.lower())
first_name="bernard"
last_name="joseph"
full_name= f"{first_name} {last_name}"
print(f"{full_name.title()}!, how are you doing")
print(8/2) #we write comments here
bicycles=["trek", "decathelon", "redlines"]
message=f"my first bicycle was a {(bicycles[1])}"
print(message)
friend_list=["fikayo", "david", "luke"]
print(f"hello {(friend_list[0])}, how are you")
print(f"hello {(friend_list[1])} whats good?" )
friend_list.append("bella")
print(friend_list[0])
friend_list.insert(2, "briade")
print(friend_list)
print(friend_list[0])
del friend_list[3]
print(friend_list)
pop_firend_list=friend_list.pop() #the removed item in the list is going to be stored here
print(f" \n i dont talk with {pop_firend_list} anymore lol")
print(friend_list)
too ="briade"
friend_list.remove(too)
print(f"{too} is a super nice guy")
guest_list=["fikayo", "david", "henri"]
print(f"hello {(guest_list[0])}, im sending you a dinner invite")
print(f"hello {(guest_list[1])}, im sending you a dinner invite")
print(f"hello {(guest_list[2])}, im sending you a dinner invite")
print(f"{(guest_list[2])}, cant make if to dinner ")
guest_list[2]="joe"
print(f"hello {(guest_list[0])}, im sending you a dinner invite")
print(f"hello {(guest_list[1])}, im sending you a dinner invite")
print(f"hello {(guest_list[2])}, im sending you a dinner invite")
print(guest_list)
guest_list.insert(0, "tony")
guest_list.insert(2, "duncan")
guest_list.append("mack")
print(guest_list)
print(f"hello {(guest_list[0])}, im sending you a dinner invite")
print(f"hello {(guest_list[1])}, im sending you a dinner invite")
print(f"hello {(guest_list[2])}, im sending you a dinner invite")
print(f"hello {(guest_list[3])}, im sending you a dinner invite")
print(f"hello {(guest_list[4])}, im sending you a dinner invite")
print(f"hello {(guest_list[5])}, im sending you a dinner invite")
print("unfortunately i can send 2 invites")
print(f"im sorry {guest_list.pop()} i cant invite you any longer to dinner")
print(f"im sorry {guest_list.pop()} i cant invite you any longer to dinner")
print(f"im sorry {guest_list.pop()} i cant invite you any longer to dinner")
print(f"im sorry {guest_list.pop()} i cant invite you any longer to dinner")
print(f"hello {(guest_list[0])}, im sending you a dinner invite")
print(f"hello {(guest_list[1])}, im sending you a dinner invite")
del guest_list[0]
del guest_list[0]
print(guest_list)
cars=["bmw", "hyundai", "ford"]
print(cars)
cars.sort()
print(cars)
cars.sort(reverse=True)
print(cars)

cars1=["benz","audi", "toyota", "chevrolet"]
print(cars1)
f=sorted(cars1)
print("\t here is the sorted list")
print(f)
print(cars1)
print(len(cars1))
places=["norway", "japan","us", "kenya"]
print(places)
print(sorted(places))
print(places)
places.reverse()
print(places)
places.reverse()
print(places)
places.sort()
print(places)
places.sort(reverse=True)
print(places)
num=len(places)
print(num)
for place in places:
    print(f"i would like to visit {place}")
print("\n")
print("they are nice places to visit\n")
animals=["dog", "cat", "horse"]
for animal in animals:
    print(animal)
    print("A "+ animal +" is mans best friend")
for values in range(1, 5):
    print (values)
numbers= list(range(2,11,2))
print(numbers)
squares=[]
for value in range(1, 11):
    square=value**2
    squares.append(square)
print(squares)
print(min(squares))
print(max(squares))
print(f" the sum of the numbers in the list is {sum(squares)}")
# for num in range(1, 1000000):
    # print(num)

for num in range(1, 21, 2):
    print(num)
cube=[]
for num in range(3, 31, 3):
    cube.append(num)

print(cube)

#for value2 in range(1, 11):
   # cubee=value2**3  
   # print(cubee)
cubee=[value2**3 for value2 in range(1, 11)]
print(cubee)
# slicing the list cube
slice1=(cubee[0:5])
slice2=(cubee[5:])
print(slice1, "    ", slice2)
players=["john", "Mark", "brown", "david", "florence"]
print("this are the player in my teamn\n")
for player in players:
     print (player)
print("\n")
print("but the available players are:\n")
for player in players[:3]:
     print (player.title())
print("\n")
dimensions=(200, 50)
#print(dimensions[0])
#print(dimensions[1])
for dimension in dimensions:
    print(dimension)

cars=["bmw", "Honda", "Hyundai", "Subaru"]
for car in cars:
    if car =="Honda":
        print(car.upper())
    else:
         print(car.title())

age=17
if age>=18:
    print("you are old enough to vote!!!")
    print("Have you registered to vote yet?")#
else:
    print("you are not yet eligible to vote")
    print("please register as soon as you turn 18!")

age=13
if age <4:
    price=0
elif age < 18:
    price=25
else:
    price=40
print("you are", age,)
print(f"your admission cost is ${price}.")
alien_color=["green", "blue"]
if "green" in alien_color:
    print("you earned 5 points")
else:
    print("no point earned")
alien_0={'color':'green', "points": 5}
print(alien_0["color"])
print(alien_0['points'])
alien_0["x_position"]=0
alien_0["y_position"]=25
print(alien_0)
alien_1={}#empty dictionary
alien_1['color']='blue'
alien_1['points']=6
print(f"the alien is {alien_1['color']}.")
alien_1['color']='yellow'
print(f"the alien is now {alien_1['color']}.")
alien3={'xposition':0, 'yposition':25, 'speed':'fast'}
print(f"Original x-cordinate: {alien3['xposition']}")
if alien3["speed"]=='slow':
    xincrement=1
elif alien3["speed"]=='medium':
    xincrement=2
elif alien3["speed"]=='fast':
    xincrement=3

alien3["xposition"]= alien3["xposition"]+ xincrement
print(f"New position: {alien3['xposition']}")
del alien_0["color"]
print(alien_0)
favorite_language={
    'jen': 'python',
    'sarah': 'c',
    'edward': 'ruby',
    'phil': 'python',
}

language= favorite_language["sarah"].title()
print(f"sarah's favorite languege is {language}")
alien_0={'color': 'green', 'speed': 'slow'}
cl=alien_0.get('speed', 'Not available')
print(cl)
person={
    'first_name': 'mark',
    'last_name': 'cube',
    'age': 21,
    'city': 'Port Harcourt'
    }
full_name=f"{person['first_name']} {person['last_name']}"
print(f"Hello {full_name}! you live in {person['city']}, and you are {person['age']}.")
for key, value in person.items(): # you can say --- for k, v in person
    print(f"\nKey: {key}")
    print(f"value: {value}")

for name, language in favorite_language.items():
    print(f"{name.title()}'s favourite langauge is {language}\n")

##for name in favorite_language.keys():
    ##print(name.title())

favorite_language={
    'jen': 'python',
    'sarah': 'c',
    'edward': 'ruby',
    'phil': 'python',
    
}
friends=['sarah', 'phil']
for name, language in favorite_language.items():
    print()
    print(name)
    print(language)
cl=favorite_language.get("\nmike", "Not available\n")
print(cl)
#for name in favorite_language.keys():
   # print (name.title())

friends=['phil', 'sarah'] #to greet our friends if they on the friend list.
for name in favorite_language.keys():
    print(name.title())
    if name in friends:
        print(f"Hi {name.title()}, i see your favourite language is {favorite_language[name]}!")
if 'erin' not in favorite_language.keys():
    print('Erin, please take our poll')
for name in favorite_language.keys():
    print(name.title())
for name in sorted(favorite_language.keys()):
    print(f"{name.title()}, thank you taking our poll.\n")

print('The following language has been mentioned:')
for language in favorite_language.values():
    print(language.title())
# exercise - make a dictionary containing river and the country each runs through
River={
    'nile':'egypt',
    'Benue':'nigeria',
    'zambezi': 'zambia'
    }
for river, country in River.items():
    print(f"The River {river} flows through {country}\n")

#for river in River.keys():
    #print(river)

#for country in River.values():
    #print(country)

people=['jen', 'sarah', 'edward', 'phil', 'edi', 'ann', 'henri', 'fikayo']
print('people surveyed:')
for person in people:
    print(person)
    #if person not in favorite_language.keys():
        #print(person)
for name in favorite_language.keys():
    #print(name.title())
    if name in people:
        print(f"{name}, thanks for having the poll\n")

for person in people:
   if person not in favorite_language.keys():# code checks the name in people list to check they are not in favourite language dictionary
        print(f'Hello {person}, could you please answer the poll?\n')

#code for nesting in dictionaries
alien_0={'color':'green', 'points':5}
alien_1={'color':'yellow', 'points':10}
alien_2={'color':'red', 'points':15}
#different dictionaries for each alien.
aliens=[alien_0,alien_1, alien_2] #list contains all the alien 
for alien in aliens:
    print(alien)

# Make an empty list for storing aliens.
aliens = []
 #Make 30 green aliens
for alien_number in range(30): #this makes 30 aliens
    new_alien = {'color': 'green', 'points': 5, 'speed': 'slow'}
    aliens.append(new_alien)

for alien in aliens[:5]:
    print(alien)
print("...")
#Show how many aliens have been created.
print(f"total number of aliens: {str(len(aliens))}") # the str is redundant but its nice to leave it there
#squares=[]
#for number in range(1,5): #this code is similar with line 309
    #square=number**2
   # squares.append(square)
#print(squares)  
#to change the characteristics of the first 3 aliens.
for alien in aliens[:3]:
    if alien['color']=='green':
        alien['color']='yellow'
        alien['speed']='medium'
        alien['points']=10
    elif alien['color'] == 'yellow':
         alien['color'] = 'red'
         alien['speed'] = 'fast'
         alien['points'] = 15

for alien in aliens[:5]:
    print(alien)
print("...")
#new heading/ a list in a dictionary.
pizza={
    'crust': 'thick',
    'toppings':['mushrooms', 'extra cheese'] 
}
#for key, value in pizza.items():
 #   print(key)
  #  print(value)


#print(pizza['crust'])
#for topping in pizza.values():
 #   print( topping)

print ('you ordered a ' + pizza ["crust"] + '-crust pizza' +  ' with the following toppings:')
for topping in pizza["toppings"]:
    print (topping)

favorite_language={
    'jen': ['python', 'php'],
    'sarah': ['c', 'c#', 'go'],
    'edward': ['ruby', 'c++'],
    'phil': ['python','pearl']
}

for name, languages in favorite_language.items():
    print(f"\n{name.title()}'s favourite langusges are:")
    for language in languages:
        print(f" \t {language.title()}")

#a dictionary in a dictionary
users = {
'aeinstein': {
'first': 'albert',
'last': 'einstein',
'location': 'princeton',},
'mcurie': {
'first': 'marie',
'last': 'curie',
'location': 'paris',
}}

for username, user_info in users.items():
    print(f"\nusername: {username}")
    full_name=f"{user_info['first']} {user_info['last']}"
    location=user_info['location']
    print(f"\tfullname: {full_name.title()}")
    print(f"\tlocation: {location.title()}")


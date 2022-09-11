#Dimuthu_Praboda
#Inspired from Raamuwa channel
#Raamuwa Einstine Time math code

import math

C = 299792458 #speed of light
CC = C*C

#Gives Travellers Time when we put Viewers time
def t1_to_t2(t1, travellers_speed):
    vv = travellers_speed*travellers_speed

    part_1 = vv / CC
    part_2 = 1 - part_1
    part_3 = math.sqrt(part_2)

    t2 = t1 / part_3

    return t2

#Gives Viewers Time when we put Travellers time
def t2_to_t1(t2, travellers_speed):
    vv = travellers_speed * travellers_speed

    part_1 = vv / CC
    part_2 = 1 - part_1
    part_3 = math.sqrt(part_2)

    t1 = t2 * part_3

    return t1


option = input('''
What you want? 
1 - Travellers Time
2 - Viewers Time
:- ''')

if option == '1':
    T2 = float(input("Viewers Time (T2) :- "))
    Travellers_speed = float(input("Travellers speed (V) :- "))
    print(t2_to_t1(T2, Travellers_speed))

elif option == '2':
    T1 = float(input("Travellers Time (T1) :- "))
    Travellers_speed = float(input("Travellers speed (V) :- "))
    print(t1_to_t2(T1, Travellers_speed))

else:
    print("Wrong input")
    pass

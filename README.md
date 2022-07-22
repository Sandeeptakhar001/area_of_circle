# area_of_circle


import math


def area_of_circle():
    print("do you Want to calculate area of circle: press Y or N")
    command = input()
    if command == 'y' or command == 'Y':
        print("please enter radius of circle: ")
        R = float(input())
        area = 2*math.pi*R
        print(area)
    elif command == 'n' or command == 'N':
        print('goodbye')
        exit()
    else:
        print('press again')
    again()
def again():
    print('do you want to calculate again: press y or n')
    cal_again = input()
    if cal_again == 'y':
        area_of_circle()
    elif cal_again =='n':
        print('goodbye')
    else:
        again()
area_of_circle()
    

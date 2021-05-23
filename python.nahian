# health-management-system

import datetime
def gettime():
    return datetime.datetime.now()

def get(a):
    if a == 1:
        b = int(input("enter 1 for exercise and 2 for food: "))
        if b==1:
            value = input("Enter here: ")
            with open("nahianex.txt", "a") as f:
                f.write(str([str(gettime())]) + ": " + value + "\n")
            print("Successfully written.")

        elif b==2:
            value = input("Enter here: ")
            with open("nahianfood.txt", "a") as f:
                f.write(str([str(gettime())]) + ": " + value + "\n")
            print("Successfully written.")


    if a==2:
        b = int(input("enter 1 for exercise and 2 for food: "))
        if b == 1:
            value = input("Enter here: ")
            with open("nasifex.txt", "a") as f:
                f.write(str([str(gettime())]) + ": " + value + "\n")
            print("Successfully written.")

        elif b == 2:
            value = input("Enter here: ")
            with open("nasiffood.txt", "a") as f:
                f.write(str([str(gettime())]) + ": " + value + "\n")
            print("Successfully written.")


def retrieve(a):
    if a == 1:
        b = int(input("enter 1 for exercise and 2 for food: "))
        if b == 1:
            with open("nahianex.txt") as f:
                for i in f:
                    print(i , end="")

        elif b == 2:
            with open("nahianfood.txt") as f:
                for i in f:
                    print(i , end="")

    if a == 2:
        b = int(input("enter 1 for exercise and 2 for food: "))
        if b == 2:
            with open("nasifex.txt") as f:
                for i in f:
                    print(i, end="")

        elif b == 2:
            with open("nasiffood.txt") as f:
                for i in f:
                    print(i, end="")


c = int(input("Press 1 for get and 2 for retrieve: "))

if c == 1:
    d = int(input("Press 1 for nahian and 2 for nasif: "))
    get(d)

elif c == 2:
    d = int(input("Press 1 for nahian and 2 for nasif: "))
    retrieve(d)

else:
    print("Error!!!!")


# MD. NAHIAN AHMED


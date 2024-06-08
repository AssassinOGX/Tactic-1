import random


while True:
    elements = "+-/*!&$#?=@abcdefghijklnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ1234567890"
    pass_length = int(input("Ingrese la longitud de pase: "))

    password = ""


    for i in range(pass_length):
        password += random.choice(elements)

    print(password)

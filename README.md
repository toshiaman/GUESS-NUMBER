# GUESS-NUMBER
# guess number in python code 
n = 40
i = 0
print("number b/w 0 to 40")
print('you have only 9 try')
while (i < 9):
    i = i + 1
    print('LIFE',int(i))

    a=9-int(i)
    print('life left',int(a))
    inp = int(input("enter the your number\n"))
    while (inp == n):
            print('number of life you took', int(i))
            print('you win')

            i+=10
            break
    if inp > n:
        print(' number is greater')
    elif inp < n:
        print('number is lesser')
        continue
print('game over')




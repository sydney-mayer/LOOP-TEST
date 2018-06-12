# LOOP-TEST
print('Welcome to Wald der Ratsel. Do you want to play?')
print('Type YES if ready')
print('Type NO if not ready')
print(' ')
a = input()
while True:
    if a == 'NO':
        print(' ')
        print('Okay, come back when you are ready.')
        a=input('Do you want to play?')
        
    elif a =='YES':
        print('Okay! Beginning your journey...')
        print(' ')
        break
    if a == 'YES':
        print(' ')
        print('You wake up on a bed of moss in a large forest;')

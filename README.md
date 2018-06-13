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
        a = input('Do you want to play?')

    elif a == 'YES':
        print('You wake up on a bed of moss in a large forest;')
        print('the sun is just beginning to make its way into the sky,')
        print('and the soft orange glow of early morning light streams')
        print('through the trees. You are confused as to where you are')
        print('and how you got here. You get up and dust yourself off,')
        print('and feel a small object in your pocket. Taking it out, you')
        print('recognize it to be a small lighter. You put it back in')
        print('your pocket. There is not much around you, to your left is')
        print('a river and to your right is a small dirt path.')
        print(' ')
        print('Do you want to go LEFT or RIGHT?')
        break
    if a == 'YES':
        print(' ')
        print('Okay! Beginning your journey...')
        print(' ')

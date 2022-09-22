# QuizzGameUsingPython

print('Welcome to my quiz game!')

playing =input('Do you wan to play the game?')

if playing.lower() != 'yes':
    quit()

print('Good! Lets play :)')

score = 0

answer = input('What does FIFA stands for?')
if answer.lower() == 'federation internationale de football association':
    print('Correct')
    score +=1
else:
    print('Incorrect')


answer = input('What does UCL stands for?')
if answer.lower() == 'uefa champions league':
    print('Correct')
    score += 1
else:
    print('Incorrect')


answer = input('Who scored most goals for Barcelona football club?')
if answer.lower() == 'messi':
    print('Correct')
    score += 1
else:
    print('Incorrect')


answer = input('Which club has the most UCL titles?')
if answer.lower() == 'real madrid':
    print('Correct')
    score += 1
else:
    print('Incorrect')


answer = input('Which player has most ballondor?')
if answer.lower() == 'messi':
    print('Correct')
    score += 1
else:
    print('Incorrect')

print('You answered'+' '+str(score)+' '+'questions correctly')
print('You answered'+' '+str((score/5) * 100)+' '+'%')

print('Welcome to my quiz game!')

playing =input('Do you wan to play the game?')

if playing.lower() != 'yes':
    quit()

print('Good! Lets play :)')

score = 0

answer = input('What does FIFA stands for?')
if answer.lower() == 'federation internationale de football association':
    print('Correct')
    score +=1
else:
    print('Incorrect')


answer = input('What does UCL stands for?')
if answer.lower() == 'uefa champions league':
    print('Correct')
    score += 1
else:
    print('Incorrect')


answer = input('Who scored most goals for Barcelona football club?')
if answer.lower() == 'messi':
    print('Correct')
    score += 1
else:
    print('Incorrect')


answer = input('Which club has the most UCL titles?')
if answer.lower() == 'real madrid':
    print('Correct')
    score += 1
else:
    print('Incorrect')


answer = input('Which player has most ballondor?')
if answer.lower() == 'messi':
    print('Correct')
    score += 1
else:
    print('Incorrect')

print('You answered'+' '+str(score)+' '+'questions correctly')
print('You answered'+' '+str((score/5) * 100)+' '+'%')


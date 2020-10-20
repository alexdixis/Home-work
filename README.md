run = int(input('Введите сколько пробежал'))
goal = int(input('Введите сколько цель пробежать'))
day = 1
while float(run) < float(goal):
    day+=1
    run= run * 1.1
    print("in" ,day, "you reach the goal")

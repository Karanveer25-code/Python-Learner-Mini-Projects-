# Python-Learner-Mini-Projects-
Rock,Paper,scissors Game

rock='''        ,--.--._
------" _, \___)
        / _/____)
        \//(____)
------\     (__)
       `-----" '''

scissors='''   _       ,/'
   (_).  ,/'
   __  ::
  (__)'  `\.
            `\.'''
            
paper='''  _ __   __ _ _ __   ___ _ __ 
| '_ \ / _` | '_ \ / _ \ '__|
| |_) | (_| | |_) |  __/ |   
| .__/ \__,_| .__/ \___|_|   
| |         | |              
|_|         |_|             '''

import random
list=[rock,scissors,paper]
com_idx=random.randint(0,2)
computer_choice=list[com_idx]
choose=int(input('What do you choose? Type 0 for Rock, 1 for scissors or 2 paper'))
if choose==0:
    print(list[0])
    print(f'''Computer Choose:     
{computer_choice}''')
    if choose==0 and com_idx==0:
        print('Draw')
    elif choose==0 and com_idx==1:
        print('You Win')
    else:
        print('You lose')
    

elif choose==1:
    print(list[1])
    print(f'''Computer Choose:     
{computer_choice}''')
    if choose==1 and com_idx==1:
        print('Draw')
    elif choose==1 and com_idx==0:
        print('You Lose')
    else:
        print('You Win')

elif choose==2:
    print(list[2])
    print(f'''Computer Choose:     
{computer_choice}''')
    if choose==2 and com_idx==2:
        print('Draw')
    elif choose==2 and com_idx==1:
        print('You Lose')
    else:
        print('You Win')



       

    






















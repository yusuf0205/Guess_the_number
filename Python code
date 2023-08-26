import random
a= random.randint(1,100)
print('Welcome to Guess the Number')
print('-------------------------------------------------------')
print('''
      level:
 	 1.level Easy 50 turns
	  2.level Intermediate 25 turns
	  3.level Hard 10 turns
	   ''')
print('-------------------------------------------------------')
p= int(input('Enter Level: '))
if p==1:
	n=50
elif p==2:
	n=25
elif p== 3:
	n=10
for i in range(0,n) :
	b= int(input('Guess the number: '))
	if b>a:
		print('too high')
	elif b==a:
		print('Congratulations ')
		j=1
		break
	else:
		print('too low')
if j!=1:
	print('Oops! Turns over')

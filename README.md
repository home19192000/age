"# age" 
#age
driving = input('請問你有没有開過車')
if driving != 'yes' and driving !='no':
    print('只答yes or no la ')
    raise SystemExit


age = input('請問你的年齡')
age = int(age)
if driving == 'yes':
	if age >= 18:
		print('pass!!!')
	else:
		print('那你為什麼開過車')
elif driving == 'no':
	if age >= 18:
		print('你可以去考了')
	else:
		print('過幾年去考吧')

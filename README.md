lst=[-1,-2,-3,0,0,5,6,7,8]
positive=0
negative=0
zeroes=0
for i in lst:
    if(i>0):
        positive+=1
    elif(i<0):
        negative+=1
    else:
        zeroes+=1
print('no.of positive numbers =',positive)
print('no.of negative numbers=',negative)
print('no.of zeroes=',zeroes)

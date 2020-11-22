# find-prime
num = 1000
mark=0
sum=0
for i in range(2,num+1):
    mark=1
    for j in range(2,i):
        if(i%j==0):
            mark=0
    if(mark==1):
        sum+=1
print('total prime : ',sum)    

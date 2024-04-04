C= [1,2,3,4,5,6,7,8,9,10]
n=len(C)
sum =0
d=0
j=0
for i in range(n) :
    if i%2==1 :
        j = j + 1
        sum += C[i]
        d=sum/j
        print(d)

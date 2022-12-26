# 11.sum-of-n-prime-numbers
n = int(input())
s=0
for i in range (1,n):
    f=0
    for j in range(1,i+1):
        if i%j==0:
            f=f+1
    if f==2:
        print(i)
        s=s+i
print('Their sum is',s)

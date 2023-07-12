# JudgingDelay
# cook your dish here
t=int(input())
while t:
    c=0
    for i in range(int(input())):
        a,b=map(int,input().split())
        if(abs(a-b)>5):
            c+=1
    print(c)
    t-=1

# CarRange
# cook your dish here
t=int(input())
while t:
    p,m,v=map(int,input().split())
    print((m-(p-1))*v)
    t-=1

#diwallii
def max(N,P):
    remain=240-P
    pro=0
    for i in range(1,N+1):
        if remain>=5*i:
            pro+=1
            remain-=5*i
        else:
            break
    return pro
N=int(input("enter: "))
P=int(input("gg:"))
print(max(N,P))
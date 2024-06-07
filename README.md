# python-program2
armstrong number
n=371
temp=n
s=0
while(temp!=0):
    r=temp%10
    s+=r*r*r
    temp=temp//10
if(n==s):
    print("armstrong number")
else:
    print("not armstrong number")

num=371
sum=0
temp=num
while(temp!=0):
    r=temp%10
    sum+r*r*r
    temp=temp//10
    if(sum==num):
        print("armstrong")
    else:
        print("if is not armstrong")

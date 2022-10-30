# Pull Request Signed SoW

##While collaborating with XYZ company, CAN IT Consulting has been engaged to assist in resolving this issue.

### This is the Debuging Project Code:

def lone_sum(a, b, c):
    if a >= b:
        return c
    elif a == c:
        return b
    elif b == c:
        return a
    elif a == b and a == c and b == c:
        return 0
    else:
        return a+b+c
#input the values of a, b and c from the user
a=int(input("Enter the value of a :"))
b=int(input("Enter the value of b :"))
c=int(input("Enter the value of c :"))
#function call
print(lone_sum(a,b,c) )
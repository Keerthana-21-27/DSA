# DSA
#write a code to print the sum of digits of a given number
n=int(input("Enter a number:"))
sum=0
while n!=0:
    d=n%10
    sum=sum+d
    n//=10
print("Sum of elements:",sum)

#write a code to print the reverse of a given number
n=int(input("Enter a number:"))
rev=0
while n>0:
    d=n%10
    rev=rev*10+d
    n//=10
print("Reverse of a number:",rev)

#write a code to print the count of even digits and odd digits in a given number
num=int(input("Enter the number:"))
even=0
odd=0
while num!=0:
    d=num%10
    if d%2==0:
        even+=1
    else:
        odd+=1
    num//=10
print("Even count:",even)
print("Odd count:",odd)

#write a code to check whether the given 2 strings are sorted or not
n=input("Enter 1st string:").replace(' ','').lower()
p=input("Enter 2nd string:").replace(' ','').lower()
if len(n)!=len(p):
    print("Not Anagram")
elif sorted(n)==sorted(p):
    print("Anagram")
else:
    print("Not Anagram")

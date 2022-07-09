# Assignment2
assignment2
s=input()
o=''
for i in s:
    if i.isalpha():
        o=o+i
print(*set(o))

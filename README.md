# py-30
swap with numbers
def print_even(s):
    new=""
    for i in s:
            asc=ord(i)
            if(65<=asc<=90):
                ch=chr(asc+32)
                new+=ch
            elif(97<=asc<=122):
                ch=chr(asc-32)
                new+=ch
            else:
                new+=i
    return new
print(print_even("PYTHON222"))

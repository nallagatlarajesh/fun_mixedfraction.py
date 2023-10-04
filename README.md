# fun_mixedfraction.py
def mixedfraction(num,deno=1):
    remainder=num%deno
    if remainder!=0:
        quotient=int(num/deno)
        print("the mixed fraction =",quotient ,"(",remainder ,"/",deno,")")
    else:
        print("the given fraction evaluates to a whole number")
    #function ends here
num=int(input("enetr the numerator:"))
deno=int(input("inter the denominator:"))
print("you enterd:",num,"/",deno)
if num>deno:

    mixedfraction(num,deno)
else:
    print("it is a proper function")

#input
    #num=19
     #deno=2

#output

     #you enterd: 19 / 2
     #the mixed fraction = 9 ( 1 / 2 )

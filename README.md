# python1
def fib(num):

    if num <= 1:

         return num

    else:

         return (fib(num – 1) + fib(num – 2))

nu= int(input(“Enter the number of terms you want: “))

if nu <= 0:

   print(“Give a natural number”)

else:

   for n in range(nu):

        print(fib(n),end=’,’)

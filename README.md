# 

1.Write a Python program that asks the user to enter a number and then prints "Fizz" if the number is divisible by 3, "Buzz" if the number is divisible by 5, and "FizzBuzz" if the number is divisible by both 3 and 5. If the number is not divisible by either 3 or 5, the program should just print the number
A.for fizzbuzz in range(1,100): 
 

    # Number divisible by 15,(divisible 

    # by both 3 & 5), print 'FizzBuzz' 

    # in place of the number

    if fizzbuzz % 15 == 0: 

        print("FizzBuzz")                                         

        continue
 

    # Number divisible by 3, print 'Fizz'

    # in place of the number

    elif fizzbuzz % 3 == 0:     

        print("Fizz")                                         

        continue
 

    # Number divisible by 5, 

    # print 'Buzz' in

    # place of the number

    elif fizzbuzz % 5 == 0:         

        print("Buzz")                                     

        continue
 

    # Print numbers

    print(fizzbuzz)

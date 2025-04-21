# EX-NO-6-Pseudo-Random-Number

# AIM: 
Implementation of Pseudorandom Number Generation Using Standard library

# ALGORITHM:
Start the program and import the required libraries.
Seed the random number generator using the current time(i.e) rand(time(0));
Get the number of randon number to generate.
Pass the value for number of iterations and print the numbers.
End the program.

# PROGRAM:
```
import random

def main():
    count = int(input("Enter the number of random numbers to generate: "))
    min_value = int(input("Enter the minimum value: "))
    max_value = int(input("Enter the maximum value: "))

    print("Pseudorandom numbers:")
    for _ in range(count):
        random_number = random.randint(min_value, max_value)
        print(random_number)

if __name__ == "__main__":
    main()
```

# OUTPUT:
![image](https://github.com/user-attachments/assets/77ded459-a277-470c-a395-7f132c19d07c)


# RESULT:

The implementation of Pseudorandom Number Generation using Standard library is successful.



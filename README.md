# Assingnment_18-08-2024

1- Calculate your age based on the current year and your birth year.

2- Write a program that calculates the area of a rectangle using length and width variables.

3- Write a program that calculates the area of a circle.

4- Write a program that calculates the area of the cube.

5- Create a program that converts a temperature from Fahrenheit to Celsius and vice versa using a variable.

6- Convert a given number of seconds into minutes and seconds using variables.

7- Write a program that calculates the percentage.

1-
description:
    This function calculates and displays the user's age. It prompts the user to enter their birth year and the current year, then computes and prints the age by subtracting the birth year from the current year.
function:
    print("Age Calculator")
    birth_year = int(input("Enter your Birth-Year: "))
    current_year = int(input("Enter your Current-Year: "))
    print("Your age is ", (current_year - birth_year))

2-
description:
    This function calculates and displays the area of a rectangle. It prompts the user to input the length and width of the rectangle, then computes and prints the area using the formula \( \text{length} \times \text{width} \).
function:
    print("Rectangle Area Calculator")
    rectangle_length = int(input("Enter your Rectangle-length: "))
    rectangle_width = int(input("Enter your Rectangle-Width: "))
    print("The area of your rectangle is ", (rectangle_length * rectangle_width))
    
3-
description:
    This function calculates and displays the area of a circle. It prompts the user to input the circle's radius and then computes and prints the area using the formula \( \pi r^2 \), with \(\pi\) approximated as 3.1416.
function:
    print("Circle Area Calculator")
    circle_radius = int(input("Enter your circle-radius: "))
    pie_value = 3.1416
    print("The area of the circle is: ", (pie_value * (circle_radius ** 2)))

4-
description:
    This function calculates and displays the volume of a cuboid. It prompts the user to input the length, width, and height of the cuboid, then computes and prints the volume using the formula \( \text{length} \times                 \text{width} \times \text{height} \).
function:
    print("Cube Volume Calculator")
    cube_length = int(input("Enter your Cube-Length: "))
    cube_width  = int(input("Enter your Cube-Width: "))
    cube_height = int(input("Enter your Cube-Height: "))
    print("The volume of the Cube is: ", (cube_length * cube_width * cube_height))

5-
description:
    This function converts temperatures between Celsius and Fahrenheit. It first converts Celsius to Fahrenheit using the formula \((\text{Celsius} \times \frac{9}{5}) + 32\) and then converts Fahrenheit to Celsius using \            ((\text{Fahrenheit} - 32) \times \frac{5}{9}\). It prints the results for both conversions.
    Print("\t Temperature Calculator")
function:
    print("Temperature Convertor (Celsius -> Fahrenheit)")
    temperature = int(input("Enter your temperature in Celsius: "))
    print("Temperature in Fahrenheit is: ", ((temperature * 9 / 5) + 32))
     print("Temperature Convertor (Fahrenheit -> Celsius)")
    temperature = int(input("Enter your temperature in Fahrenheit: "))
    print("Temperature in Celsius is: ", ((temperature - 32) * 5 / 9))

6-
description:
    This function converts a given time in minutes to seconds. It prompts the user to enter the time in minutes and then calculates and prints the equivalent time in seconds by multiplying the input value by 60.
function:
    print("Time Calculator (Minutes -> Seconds)")
    time_minutes = int(input("Enter your time in minutes: "))
    print("Time in seconds is: ", (time_minutes * 60))
    
7-
Description: 
    This function is a simple percentage calculator. It prompts the user to enter their percentage and the total marks, then calculates and prints the result of applying the percentage to the given marks. The formula used is         ((percentage / 100) * marks).
Function: 
    print("Percentage Calculator")
    percentage = int(input("Enter your percentage: "))
    marks = int(input("Enter your marks: "))
    print("Percentage is: ", ((percentage / 100) * marks))

8-
Description:
    This function calculates the volume of a cylinder. It prompts the user to input the radius and height of the cylinder, then computes and prints the volume using the formula \( V = \pi r^2 h \), where \(\pi\) is approximated       as 3.1416.
function:   
    iprint("Cylinder Volume Calculator (V = πr²h)")
    radius = int(input("Enter your radius: "))
    height = int(input("Enter your height: "))
    pie_value = 3.1416
    print("Volume of Cylinder is: ", pie_value * (radius ** 2) * heght)

9-
description:
    This function calculates and displays the volume of a cylinder. It asks the user to input the radius and height, then uses the formula \( V = \pi r^2 h \) (with \(\pi\) approximated as 3.1416) to compute and print the             cylinder's volume.
function:
    print("Cylinder Volume Calculator (V = πr²h)")
    radius = int(input("Enter your radius: "))
    height = int(input("Enter your height: "))
    pie_value = 3.1416
    print("Volume of Cylinder is: ", pie_value * (radius ** 2) * height)



# Assingnment_18-08-2024

1- Calculate your age based on the current year and your birth year.

2- Write a program that calculates the area of a rectangle using length and width variables.

3- Write a program that calculates the area of a circle.

4- Write a program that calculates the area of the cube.

5- Create a program that converts a temperature from Fahrenheit to Celsius and vice versa using a variable.

6- Convert a given number of seconds into minutes and seconds using variables.

7- Write a program that calculates the percentage.

1-
print("Age Calculator")
birth_year = int(input("Enter your Birth-Year: "))
current_year = int(input("Enter your Current-Year: "))
print("Your age is ", (current_year - birth_year))

2-
print("Rectangle Area Calculator")
rectangle_length = int(input("Enter your Rectangle-length: "))
rectangle_width = int(input("Enter your Rectangle-Width: "))
print("The area of your rectangle is ", (rectangle_length * rectangle_width))

3-
print("Circle Area Calculator")
circle_radius = int(input("Enter your circle-radius: "))
pie_value = 3.1416
print("The area of the circle is: ", (pie_value * (circle_radius ** 2)))

4-
print("Cube Volume Calculator")
cube_length = int(input("Enter your Cube-Length: "))
cube_width  = int(input("Enter your Cube-Width: "))
cube_height = int(input("Enter your Cube-Height: "))
print("The volume of the Cube is: ", (cube_length * cube_width * cube_height))

5-
Print("\t Temperature Calculator")

print("Temperature Convertor (Celsius -> Fahrenheit)")
temperature = int(input("Enter your temperature in Celsius: "))
print("Temperature in Fahrenheit is: ", ((temperature * 9 / 5) + 32))

print("Temperature Convertor (Fahrenheit -> Celsius)")
temperature = int(input("Enter your temperature in Fahrenheit: "))
print("Temperature in Celsius is: ", ((temperature - 32) * 5 / 9))

6-
print("Time Calculator (Minutes -> Seconds)")
time_minutes = int(input("Enter your time in minutes: "))
print("Time in seconds is: ", (time_minutes * 60))

7-
print("Percentage Calculator")
percentage = int(input("Enter your percentage: "))
marks = int(input("Enter your marks: "))
print("Percentage is: ", ((percentage / 100) * marks))

8-
print("BMI Calculator")
weight = int(input("Enter your weight in kilograms: "))
height = float(input("Enter your height in meters: "))
bmi = weight / (height ** 2)

if bmi < 18.5:
    print('Underweight')
elif 18.5 <= bmi < 25:
    print("Normal weight")
elif 25 <= bmi < 30:
    print('Overweight')
else:
    print('Obesity')

9-
print("Cylinder Volume Calculator (V = πr²h)")
radius = int(input("Enter your radius: "))
height = int(input("Enter your height: "))
pie_value = 3.1416
print("Volume of Cylinder is: ", pie_value * (radius ** 2) * height)



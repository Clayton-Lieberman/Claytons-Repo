# Object Postion Calculator in Python

*Calculates object position based on intial position, velocity, acceleration, and time past.*

~~~
xo = float(input("Enter the object's initial position: "))
vo = float(input("Enter the object's initial velocity: "))
a = float(input("Enter the object's acceleration: "))
t = float(input("Enter the time past: "))
xf = xo +vo*t + 0.5*a*t**2
print(xf)
~~~


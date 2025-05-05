Name. Ranpise Anmol
Roll No. SEL66
Date. 03/03/2025

Created on Thu Apr  3 14:32:44 2025

@author: EL-COMP LAB-2
"""

"Program for Gauss Jacobi"

def f(x,y,z):
    return(1/3*(7-4*y))
def g(x,y,z):
    return(1/11*(2+3*x+5*z))
def h(x,y,z):
    return(1/11*(-28+6*x-6*y))

x0=float(input("Enter intial value of x\t"))
y0=float(input("Enter intial value of y\t"))
z0=float(input("Enter intial value of z\t"))

n=int(input("Enter number of iterations\t"))

for i in range(n):
    print("applying %d iteration"%(i+1))
    x1=f(x0,y0,z0)
    y1=g(x0,y0,z0)
    z1=h(x0,y0,z0)
    print("the value of x is",x1)
    print("the value of y is",y1)
    print("the value of z is",z1)
    x0=x1
    y0=y1
    z0=z1
    
print("The iteration ended")

Output

Enter intial value of x	0
Enter intial value of y	0
Enter intial value of z	0
Enter number of iterations	5
applying 1 iteration
the value of x is 2.333333333333333
the value of y is 0.18181818181818182
the value of z is -2.5454545454545454
applying 2 iteration
the value of x is 2.090909090909091
the value of y is -0.3388429752066115
the value of z is -1.3719008264462813
applying 3 iteration
the value of x is 2.7851239669421486
the value of y is 0.12847483095416973
the value of z is -1.2201352366641625
applying 4 iteration
the value of x is 2.1620335587277735
the value of y is 0.3867905197732394
the value of z is -1.0963731985520115
applying 5 iteration
the value of x is 1.8176126403023471
the value of y is 0.2731122439475692
the value of z is -1.5771401605702542
The iteration ended








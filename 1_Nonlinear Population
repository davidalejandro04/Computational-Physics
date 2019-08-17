from sympy import *

f,g=symbols('f g',cls=Function)
t,kap,w0=symbols('t kap w0')
f(t)
f(t).diff(t)

print("\n" ODE to be solved:")
diffeq=Eq(f(t).diff(t,t)+kap*(f(t).diff))+(w0*w0)*f(t))

print(diffeq)
print("\n Solution of ODE:")

ff=dsolve(diffeq,f(t))
F=ff.subs(t,0)
print(ff)

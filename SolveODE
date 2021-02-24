import numpy as np
import matplotlib.pyplot as plt
from scipy.integrate import odeint

def firstorder(y,x):
	dydx =  3*x**2+2*x+1
	return dydx
	
x = np.linspace(0,10,10)	
y_pred = odeint(firstorder, 0, x)	
y_act = x**3+x**2+x+7
print(y_pred)
print(y_exp)

plt.plot(x,y_pred,label='Predicted')
plt.plot(x,y_act,'--',label='Actual')
plt.legend()
plt.show()

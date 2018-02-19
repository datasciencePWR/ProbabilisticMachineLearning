# Lista zadań 1
## Probability Refresher

### Knowledge:
-  Random variables
-  Rules of Probability for Discrete Variables
-  Marginals and conditional probability
-  pdf - probability density functions
-  pmf- Probability mass function
-  Independence, conditional Independence
-  Bayes rule

### Excersises:

1. (3 points) Write infinite random discrete values generator (integer number from given range, python generators, yield) and visualize how probability of given numbers change in time (matplotlib animation)
2. (4 points) Using generator from previous task, visualize probability of occurrence for two consecutive numbers in the stream (matplotlib animation, heatmaps) 
3. (5 points) Write a simulator for chances to be ill on a certain disease. We know that it affects from about 1 to 100 out of 50,000 people. There was developed a test to check whether the person has the disease and it is quite accurate: 
the probability that the test result is positive (suggesting the person has the disease), given that the person does not have the disease, is only 2 percent;
the probability that the test result is negative (suggesting the person does not have the disease), given that the person has the disease, is only 1 percent.
When a random person gets tested for the disease and the result comes back positive, what is the probability that the person has the disease? Check whole parameter space and visualise results.


### Sample code:

Colaboratory animation (modified [source](http://louistiao.me/posts/notebooks/embedding-matplotlib-animations-in-jupyter-notebooks/))
```python
%matplotlib inline
import numpy as np
import matplotlib.pyplot as plt

from matplotlib import animation, rc
from IPython.display import HTML
# First set up the figure, the axis, and the plot element we want to animate
fig, ax = plt.subplots()

ax.set_xlim(( 0, 2))
ax.set_ylim((-2, 2))

line, = ax.plot([], [], lw=2)
# initialization function: plot the background of each frame
def init():
    line.set_data([], [])
    return (line,)
  
  # animation function. This is called sequentially
def animate(i):
    x = np.linspace(0, 2, 1000)
    y = np.sin(2 * np.pi * (x - 0.01 * i))
    line.set_data(x, y)
    return (line,)
# call the animator. blit=True means only re-draw the parts that have changed.
anim = animation.FuncAnimation(fig, animate, init_func=init,
                               frames=100, interval=20, blit=True)
HTML(anim.to_jshtml())

```

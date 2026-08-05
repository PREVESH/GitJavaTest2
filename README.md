# GitJavaTest2
## GGGG
import matplotlib.pyplot as plt
import math
x = [1, 2, 3, 4, 5]
y = [10, 15, 13, 17, 20]
y1=[math.log(i) for i in x]
y2=[i for i in x]
y3=[i*math.log(i) for i in x]
y4=[i*i for i in x]
plt.plot(x, y1, marker='o')
plt.plot(x, y2, marker='o')
plt.plot(x, y3, marker='o')
plt.plot(x, y4, marker='o')
plt.title("Line Graph")
plt.xlabel("X-axis")
plt.ylabel("Y-axis")
plt.grid(True)
plt.show()

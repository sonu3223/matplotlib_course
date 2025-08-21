<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/4be4cf4b-19a8-4732-ae69-0840620a8839" />
# matplotlib_course

> Matplotlib Course for Beginners

   - Welcome to the Matplotlib Course for Beginners 🎉
   - This repository contains beginner-friendly examples of data visualization in Python using Matplotlib.

# Topics Covered

# Axis Functions 
– Learn how to set axis labels, limits, and ticks.
<img width="259" height="194" alt="image" src="https://github.com/user-attachments/assets/f03394f3-ba45-4ea1-b2f4-f8e15736db36" />

# Bar Plot 
– Create simple and grouped bar charts.
  <img width="288" height="175" alt="image" src="https://github.com/user-attachments/assets/038c5778-39d9-4199-90e0-9778b187ae45" />

# Box Plot 
– Visualize data distribution and outliers.
<img width="609" height="440" alt="image" src="https://github.com/user-attachments/assets/0b65e22e-ee0b-4f07-9547-1d8993f51dbc" />

# Fill Between Plot 
– Show area between curves.
<img width="414" height="258" alt="image" src="https://github.com/user-attachments/assets/866b5714-74a8-425a-8bf4-ba35ff05a819" />

# Histogram Plot
– Display frequency distributions.
<img width="591" height="457" alt="image" src="https://github.com/user-attachments/assets/857d3f47-8bed-4741-bb85-be4eaa4f2df1" />

# Linear Plot
– Draw simple line plots.
<img width="260" height="194" alt="image" src="https://github.com/user-attachments/assets/eb7b51ee-a0e2-478d-9702-4d6a4f23755d" />

# Pie Chart 
– Represent data in circular plots.
<img width="259" height="195" alt="image" src="https://github.com/user-attachments/assets/f3bedcd6-f6a1-4b87-b80b-73e6ee339669" />

# Scatter Plot
– Compare variables with scatter plots.
<img width="259" height="194" alt="image" src="https://github.com/user-attachments/assets/f773a593-d533-4bdc-94f9-9450619a5352" />

# Stack Plot
– Visualize stacked data over time.
<img width="640" height="480" alt="image" src="https://github.com/user-attachments/assets/c4cc1769-1830-4c90-a42f-7507a4b61664" />

# Stem Plot
– Create discrete plots with vertical lines.
<img width="259" height="194" alt="image" src="https://github.com/user-attachments/assets/0c84546c-3b3b-41da-8536-02c3ca9f2063" />

# Step Plot
– Create plots with stepwise data.
<img width="273" height="185" alt="image" src="https://github.com/user-attachments/assets/a1786036-00bd-4303-b1eb-2c5a3dfa63a8" />

# Subplots
– Arrange multiple plots in a single figure.
<img width="219" height="231" alt="image" src="https://github.com/user-attachments/assets/f11803f7-a2d7-4832-bb7b-ee80429b2805" />

# Save Figure 
– Export plots to image files (PNG, JPG, etc.).
  
import matplotlib.pyplot as plt
x = [1, 2, 3, 4, 5]
y = [10, 8, 6, 4, 2]
plt.plot(x, y, marker="o", color="red", label="Line Plot")
plt.title("Save Figure Example")
plt.xlabel("X-axis")
plt.ylabel("Y-axis")
plt.legend()
plt.savefig("images/savefigure.png")   # Save as PNG
plt.savefig("images/savefigure.jpg") # Save as JPG
plt.savefig("images/savefigure.pdf") # Save as PDF

plt.show()

# Requirements

  Before running the code, install the following:
- pip install matplotlib numpy
- pip install notebook

# Who is this course for?

 - Beginners in Python who want to learn data visualization

 - Students and aspiring data scientists

 - Anyone interested in making beautiful charts with Python

import matplotlib.pyplot as plt
import numpy as np

# Number of seeds
num_seeds = 1000

# Constants for the sunflower
phi = (1 + np.sqrt(5)) / 2  # Golden ratio

# Generate the points
r = np.sqrt(np.arange(num_seeds))  # Radii
theta = 2 * np.pi * np.arange(num_seeds) / phi**2  # Angles

# Convert polar coordinates to Cartesian coordinates
x = r * np.cos(theta)
y = r * np.sin(theta)

# Create the plot
plt.figure(figsize=(8, 8))
plt.scatter(x, y, s=5, color='goldenrod', edgecolor='green')
plt.title("Sunflower Pattern")
plt.axis('equal')
plt.show()import matplotlib.pyplot as plt
import numpy as np

# Number of seeds
num_seeds = 1000

# Constants for the sunflower
phi = (1 + np.sqrt(5)) / 2  # Golden ratio

# Generate the points
r = np.sqrt(np.arange(num_seeds))  # Radii
theta = 2 * np.pi * np.arange(num_seeds) / phi**2  # Angles

# Convert polar coordinates to Cartesian coordinates
x = r * np.cos(theta)
y = r * np.sin(theta)

# Create the plot
plt.figure(figsize=(8, 8))
plt.scatter(x, y, s=5, color='goldenrod', edgecolor='green')
plt.title("Sunflower Pattern")
plt.axis('equal')
plt.show()

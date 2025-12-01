# python_32
python_32


# Simple Mathematical y Function Example

import numpy as np  # For numerical operations
import matplotlib.pyplot as plt  # For plotting

# Define x values
x = np.linspace(-10, 10, 400)

# Define the mathematical function y = 2x + 5
y = 2 * x + 5

# Plot the function
plt.plot(x, y, color="red", label="y = 2x + 5")

# Add labels, title, and grid
plt.xlabel("X-axis")
plt.ylabel("Y-axis")
plt.title("Plot of y = 2x + 5")
plt.grid(True)
plt.legend()

# Display the plot
plt.show()

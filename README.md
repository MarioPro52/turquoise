# turquoiseimport matplotlib.pyplot as plt

# RGB values for turquoise
turquoise = (64/255, 224/255, 208/255)  # Normalize to [0,1] for matplotlib

# Create a plot with turquoise color
plt.figure(figsize=(2, 2))
plt.axis('off')  # Hide the axes
plt.gca().set_facecolor(turquoise)
plt.title("Turquoise Color", pad=20)
plt.show()

# Data Visualization Examples

This repository contains Python scripts demonstrating various data visualization techniques using popular libraries such as Matplotlib, Seaborn, and Plotly Express. Below are detailed explanations and examples of each visualization:

---

## Scatterplots and Barplots

### Scatterplot using Matplotlib

```python
import pandas as pd
import seaborn as sns
import matplotlib.pyplot as plt

# Load the 'tips' dataset from Seaborn
tips = sns.load_dataset('tips')

# Scatterplot: Total Bill vs Tips
plt.scatter(tips['total_bill'], tips['tip'])
plt.title("Scatterplot of Total Bill vs Tips")
plt.xlabel("Total Bill")
plt.ylabel("Tips")
plt.show()

# Scatterplot: Day vs Tips
plt.scatter(tips['day'], tips['tip'])
plt.title("Scatterplot of Day vs Tips")
plt.xlabel("Day")
plt.ylabel("Tips")
plt.show()

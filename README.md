# Matplotlib Subplot Grid Example

## Overview
This project demonstrates the use of `matplotlib` to create a 2x2 grid of subplots, each displaying a simple line plot with a pink dashed grid.

## Requirements
Ensure you have the following dependencies installed before running the script:

```sh
pip install matplotlib numpy
```

## Code Explanation
The script performs the following steps:
1. Defines `x` and `y` data arrays for each plot.
2. Creates a 2x2 subplot layout using `plt.subplot()`.
3. Plots the same line graph in three subplots and a different graph in the fourth subplot.
4. Adds a pink dashed grid to each subplot for better visualization.
5. Displays the final figure with `plt.show()`.

## Running the Script
Execute the script using Python:

```sh
python script.py
```

## Expected Output
A window displaying four subplots:
- Three identical line plots.
- One subplot with a different dataset.
- Pink dashed grid lines in each subplot for reference.

## Customization
You can modify the dataset by changing the `x` and `y` values in each subplot to visualize different trends.

## License
This project is open-source and available for modification and distribution.


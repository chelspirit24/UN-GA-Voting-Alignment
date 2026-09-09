# UN General Assembly Voting Alignment Analysis

This repository contains Python notebooks that analyze and visualize historical voting alignment in the United Nations General Assembly, specifically focusing on resolutions related to security, defense, military, and peace. The analysis compares how specific countries vote in relation to the "Great Powers" (USA, China, Russia, and the Soviet Union).

## Features
- **Data Filtering**: Filters UN General Assembly voting records to isolate resolutions pertaining to global security and defense issues based on keywords (e.g., military, nuclear, weapon).
- **Alignment Scoring**: Calculates an annual voting alignment score:
  - `1.0`: Voted the same way (Agree)
  - `0.5`: Partial agreement (e.g., one country abstained)
  - `0.0`: Voted opposite ways (Opposed)
- **Data Visualization**: Generates a line chart plotting the 3-year rolling average of alignment scores over time (spanning back to 1946) using `matplotlib`.

## Files
- **[`un.ipynb`](un.ipynb)**: A static analysis notebook that calculates and plots the voting alignment of **India (IND)** against the Great Powers.
- **[`un_interactive.ipynb`](un_interactive.ipynb)**: An interactive version of the analysis that prompts the user to enter a country name and dynamically generates the alignment chart for that specific country.
- **`2026_02_06_ga_voting.csv`**: The dataset containing the historical UN General Assembly voting records.

## Requirements
- `pandas`
- `numpy`
- `matplotlib`

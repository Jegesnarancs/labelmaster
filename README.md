# Spike Sorting and Analysis Tool

This project is an interactive Python tool for analyzing neural spike sorting data, visualizing spike metrics, and saving labeled data to a CSV file. The tool allows users to classify spike units interactively, visualize waveform and autocorrelogram plots, and compute various metrics like burstiness, half-width, peak-to-trough ratio, and firing rates.

## Features

- **Interactive Visualization**: Visualize spike data including waveforms and autocorrelograms using Matplotlib.
- **Spike Sorting Analysis**: Compute various metrics like burstiness index, half-width, peak-to-trough ratio, sliding firing rates, and more.
- **CSV Export**: Save labeled data to a CSV file, excluding unwanted data.
- **User-Friendly Interface**: Interactive buttons for easy labeling and navigation between units.

## Project Structure

- `main.py`: The main execution file that integrates all functions and initializes the interactive tool.
- `spike_analysis.py`: Contains functions and classes responsible for spike sorting analysis, metrics computation, and visualization.
- `utils.py`: Utility functions used for reading data, handling files, and general purpose helper methods.

## Prerequisites

- Python 3.7 or later
- Required Python Packages:
  - `numpy`
  - `pandas`
  - `matplotlib`
  - `spikeinterface`
  - `probeinterface`

You can install the necessary packages using:

```bash
pip install numpy pandas matplotlib spikeinterface probeinterface

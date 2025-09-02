
This repository contains the Kalman Filter Implementation only.For ready to use code implementations, and advanced examples on Kalman Filters, Extended Kalman Filter, Particle Filters.The complete StateFusion Toolkit can be requested using the following link:

https://sofiayousuf106.wixsite.com/syprogrammingandtech/about-1-2

-----------------------------------


Basic KF.ipnyb : Basic 1D Kalman Filter (Google Colab)

This notebook demonstrates a 1D Kalman Filter for position estimation using noisy measurements. 
It shows how noisy GPS-like data can be smoothed using a simple Kalman Filter.

Features
- Generates synthetic noisy measurements.
- Implements Kalman Filter with prediction and update steps.
- Visualizes:
  - True position (green line)
  - Noisy measurements (red dots)
  - Kalman Filter estimates (blue line)

Requirements
This notebook runs directly in Google Colab. The required libraries (numpy, matplotlib) are already available.

How to Use
1. Open the notebook in Google Colab.
2. Run all cells sequentially.
3. The final cell will display a plot showing:
   - True Position (green)
   - Measurements (red)
   - Kalman Filter Estimate (blue)

Expected Output
- A plot comparing the true position, noisy measurements, and Kalman Filter estimates.
- The Kalman Filter smooths the noisy measurements and provides an accurate trajectory estimate.




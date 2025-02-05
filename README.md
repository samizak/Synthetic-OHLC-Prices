# Synthetic OHL Price Generation
An interactive Python tool for generating synthetic financial time series data (OHLC format) using Geometric Brownian Motion (GBM) and visualizing it using matplotlib.

---

# Synthetic OHLC Price Generation

An interactive Python tool for generating synthetic financial time series data in **OHLC (Open, High, Low, Close)** format using **Geometric Brownian Motion (GBM)** and visualizing it with `matplotlib`.

---

## Features

- 📈 **Generate synthetic closing prices** using Geometric Brownian Motion (GBM).
- 🕰 **Simulate realistic intra-period price movements**:
  - High and Low prices are generated based on user-defined volatility and intra-day steps.
- 🎚 **Interactive controls** for adjusting key parameters:
  - **Drift (μ)**: Controls the average rate of return.
  - **Volatility (σ)**: Determines the variability of returns.
  - **Number of intra-day steps**: Adjusts the granularity of intra-period price movements.
- 🔄 **Real-time updates**:
  - The chart dynamically regenerates when parameters are adjusted.
- ⚖ **Toggle between linear and logarithmic scales**:
  - Switch between linear and log scales for better visualization of exponential trends.

---

## Prerequisites

To run this tool, ensure you have the following installed:

- **Python 3.7+**
- Required libraries:
  ```bash
  pip install numpy pandas matplotlib mplfinance

---

## How It Works

### Data Generation
- **Geometric Brownian Motion (GBM)**: Simulates daily closing prices based on user-defined drift (μ) and volatility (σ).
- **Intra-Day Price Simulation**: Generates high-resolution intra-day price movements between open and close prices, ensuring consistency with the overall trend.

### Interactive Controls
- Use sliders to adjust drift (μ), volatility (σ), and the number of intra-day steps.
- Click "Generate New Data" to create a new synthetic dataset.
- Toggle the "Log Scale" button to switch between linear and logarithmic y-axis scales.

### Visualization
- Candlestick charts display the synthetic OHLC data, providing an intuitive representation of price movements.
- A 20-period moving average (MAV) is overlaid on the chart for additional context.

---

## Applications

This tool is useful for various applications in finance, education, and research:
- **Education**: Understand how financial models behave under different conditions, such as varying drift and volatility.
- **Algorithm Testing**: Test trading strategies or algorithms on synthetic data before deploying them in real-world scenarios.
- **Research**: Explore the impact of drift, volatility, and intra-day granularity on price movements.

---

## Sample Visualizations

### High Volatility
![High_vol](https://github.com/user-attachments/assets/d3cc4450-b0aa-4080-8f5f-0aa7e4a0735a)

### Low Volatility
![Low_vol](https://github.com/user-attachments/assets/4db30817-c077-4f77-8872-51311fff1646)

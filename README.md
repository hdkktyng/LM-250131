# Logistic Map Visualization

This project provides an interactive visualization of the logistic map using JavaScript and Chart.js. It allows users to explore the behavior of the logistic map through cobweb plots and time series graphs.

## Features

- **Cobweb Plot**: Displays the logistic map trajectory (`x(n)` vs `x(n+1)`).
- **Time Series**: Shows the evolution of `x` over iterations (`x(n)` vs `n`).
- **Interactive Controls**:
  - Set the logistic map parameter `a`.
  - Specify the initial value `x₀`.
  - Adjust the maximum number of iterations.
  - Step through iterations manually or run automatically.
  - Pause the simulation using the stop button.
  - Reset to initial conditions.

## Usage

1. Clone this repository or download the project files.
2. Open the `index.html` file in any modern browser.
3. Use the controls to:
   - Adjust parameters (`a`, `x₀`, `Max Iterations`).
   - Observe the behavior of the logistic map through the plots.

### Controls
- **a**: Controls the parameter `a` of the logistic equation.
- **x₀**: Sets the initial value of `x`.
- **Max Iterations**: Specifies the total number of iterations for the logistic map.
- **Step Button**: Advances the simulation by one step.
- **Run Button**: Runs the simulation until the maximum number of iterations is reached.
- **Stop Button**: Pauses the simulation.
- **Reset Button**: Resets all parameters and plots.

## How It Works

The logistic map is a mathematical function:
```
x(n+1) = a * x(n) * (1 - x(n))
```

This visualization provides two key graphs:
1. **Cobweb Plot**: Illustrates the relationship between `x(n)` and `x(n+1)`.
2. **Time Series**: Tracks the value of `x` over iterations.

Both graphs update dynamically as you interact with the controls.

## Dependencies

- [Chart.js](https://www.chartjs.org/) (MIT License)

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

## Author

This project was created for educational purposes, helping students understand the logistic map and its properties interactively.

## Credits

This project was created by nagi with assistance from ChatGPT as a coding and brainstorming tool.


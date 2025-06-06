📄 Week1_Simulating_Market_Data/README.md
markdown
Copy
Edit
# Week 1: Simulating Market Data with Python

This project simulates basic economic market data, including price, demand, and cost, for use in future Industrial Organization (IO) empirical analysis.

## 🎯 Objectives

- Review basic Python syntax (lists, loops, functions)
- Practice working with Pandas, Numpy, and Matplotlib
- Generate synthetic data (demand, cost) using random noise
- Export a clean CSV file to be used for regression later
- Plot demand and cost curves

## 📁 Folder Structure

Week1_Simulating_Market_Data/
├── data/ # CSV file of simulated data
├── notebooks/ # Jupyter Notebook for this project
├── scripts/ # Python module to generate data
├── results/ # Plot images
└── README.md # Project documentation

## 🛠 Tools Used

- Python 3.10
- Numpy
- Pandas
- Matplotlib
- VS Code
- Git + GitHub

## 🧠 Key Concepts

- Simulated demand model: `Q = a - bP + ε`
- Simulated cost function: `C = c + dP + ε`
- `np.random.normal()` is used to add noise to simulated data

## 📈 Example Code

```python
price = np.linspace(1, 20, 100)
demand = 100 - 3 * price + np.random.normal(0, 5, 100)
cost = 5 + 0.3 * price + np.random.normal(0, 1, 100)
✅ Next Steps
Visualize demand/cost functions

Use the dataset for Week 5 econometric estimation

Extend simulation to include Cournot competition

🔗 License
MIT License

See [resources/resources.md](resources/resources.md) for a list of learning materials used in this project.

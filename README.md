# Irodov Visualized

This repository contains Python-based visualizations for problems from I.E. Irodov's "Problems in General Physics". The goal is to help students understand physical phenomena through interactive plots, figures, and animations, making complex physics concepts more intuitive and accessible.

## Project Overview

Each problem from Irodov's book is implemented as a separate Jupyter notebook containing:
1. The original problem statement
2. A detailed mathematical explanation of the solution
3. Python code for visualizing the physical phenomena
4. Interactive plots, animations, and vector diagrams where appropriate

The visualizations aim to provide deeper insights into the physical principles at work, helping students develop intuition beyond the mathematical formalism.

## Repository Structure

The repository is organized by physics topics, following the structure of Irodov's book:

```
IrodovVisualized/
├── Mechanics/
│   ├── Kinematics/
│   │   └── Problem_1_1.ipynb  # Motorboat and raft problem
│   ├── FundamentalDyamics/
│   ├── EnergyandMomentum/
│   ├── Gravitation/
│   ├── SolidBodyDynamics/
│   ├── HydroDynamics/
│   └── RelativisticMechanics/
├── Thermodynamics/
├── Electrodynamics/
├── Optics/
└── AtomicAndNuclearPhysics/
```

Each topic directory contains subdirectories for specific subtopics, and each problem is implemented as a separate notebook to keep the content focused and manageable.

## Setup and Installation

### Prerequisites
- Python 3.x
- Virtual environment (recommended)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/IrodovVisualized.git
   cd IrodovVisualized
   ```

2. Create and activate a virtual environment:
   ```bash
   python3 -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

## Usage

Navigate to the specific problem you're interested in and open the corresponding Jupyter notebook. Each notebook is self-contained with all the necessary code and explanations.

The notebooks include:
- Theoretical explanations with mathematical derivations
- Static visualizations (plots, diagrams)
- Dynamic visualizations (animations) where applicable
- Interactive elements for parameter exploration

## Contributing

Contributions are welcome! If you'd like to add visualizations for more problems or improve existing ones, please:

1. Fork the repository
2. Create a new branch for your feature
3. Add your visualization following the established pattern
4. Submit a pull request

## License

This project is open source and available under the MIT License.

## Acknowledgments

- I.E. Irodov for his excellent collection of physics problems
- The Python scientific computing ecosystem (NumPy, Matplotlib, SciPy, etc.)

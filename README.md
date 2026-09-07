# AGV Energy Optimization

This repository provides tools and example notebooks for path planning and energy-consumption optimization for Automated Guided Vehicles (AGVs) in warehouse and logistics environments. It implements core algorithms for route finding, order batching and multi-AGV coordination and includes utilities to evaluate and compare energy usage for different scheduling and routing strategies.

Key features

- Batch order assignment and multi-AGV coordination
- Energy consumption modeling and evaluation
- Support for multiple path-planning algorithms (Dijkstra, A*), and heuristics such as Ant Colony Optimization (ACO)
- Modular and extensible codebase so you can add new algorithms or energy models
- Example Jupyter notebooks for running experiments and visualizations

Quick start

1. Clone the repository

```bash
git clone https://github.com/yilinnntsaiii/warehouse-agv-optimizer.git
cd warehouse-agv-optimizer
```

2. (Optional but recommended) Create and activate a virtual environment, then install dependencies. This project assumes Python 3.8+.

```bash
python -m venv .venv
# macOS / Linux
source .venv/bin/activate
# Windows (PowerShell)
# .\.venv\Scripts\Activate.ps1
pip install -r requirements.txt
```

If you do not have a requirements.txt file yet, install these common dependencies as a starting point:

```bash
pip install numpy networkx matplotlib jupyter
```

Usage

- Run the example script:

```bash
python main.py
```

- Open the interactive notebooks (if present) at `notebooks/demo.ipynb` or run them on Colab. If the notebooks or requirements file are located in a different path, update the paths below accordingly.

Project structure (suggested)

```
warehouse-agv-optimizer
├── README.md            # this file
├── main.py              # example entrypoint: run experiments and visualize results
├── energy.py            # energy model and helper functions
├── requirements.txt     # Python dependencies (optional)
└── notebooks/           # Jupyter notebooks with example experiments
    └── demo.ipynb
```

Notes and recommendations

- Python version: this project targets Python 3.8 or newer.
- If `requirements.txt` or `notebooks/demo.ipynb` are missing, consider adding them to improve reproducibility and onboarding for new users.
- Add a LICENSE file (for example, MIT) to make reuse terms explicit.

Contributing

Contributions are welcome. Suggested workflow:

1. Fork the repository
2. Create a topic branch for your changes
3. Open a pull request describing the change and why it is needed

License

Add a LICENSE file in the repository root (e.g. MIT License).

Contact

If you have questions or find issues, please open an issue on GitHub or contact the repository owner.

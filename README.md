# AGV Energy Optimization

This project focuses on energy consumption optimization and path planning for Automated Guided Vehicles (AGVs) in warehouse and logistics environments. We combine path planning algorithms (e.g., Dijkstra, Ant Colony Optimization) with an energy model, and support multi-AGV scheduling and energy calculations.

## Key Features

- Batch order assignment and multi-AGV coordination
- Energy consumption evaluation and optimization
- Supports multiple path planning and scheduling algorithms (Dijkstra, ACO, etc.)
- Modular, extensible design
- Colab / Jupyter Notebook demos and visualizations

## Project Structure

warehouse-agv-optimizer/
├── README.md
├── main.py
└── energy.py

## How to use

1. Clone or download this repository
2. Install dependencies (see `requirements.txt`)
3. Run `main.py` or open `demo.ipynb` under the notebook/ folder to try the examples

```bash
git clone https://github.com/yilinnntsaiii/warehouse-agv-optimizer.git
cd warehouse-agv-optimizer
pip install -r requirements.txt
python main.py

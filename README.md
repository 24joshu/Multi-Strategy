# Multi-Strategy

🧩 Multi-Strategy Optimization Web App

This project is a Flask-based web application that demonstrates solving combinatorial optimization problems using multiple algorithmic strategies.
It supports Traveling Salesman Problem (TSP), Knapsack Problem, and Graph Matching, allowing users to compare algorithms such as Greedy, Dynamic Programming, Backtracking, Branch & Bound, Divide & Conquer.

🚀 Features

📂 Upload custom datasets (.csv / .json)

📊 Solve optimization problems:

Traveling Salesman Problem (TSP)

Knapsack Problem

Graph Matching (using NetworkX)

⚡ Multiple Algorithms:

Greedy Heuristic

Dynamic Programming

Backtracking Search

Branch & Bound

Divide & Conquer

⏱️ Benchmark multiple algorithms on the same dataset

🌐 Simple Web UI (Flask + Jinja templates)

📥 Download uploaded/processed data

🏗️ Project Structure
my-project/
│── MULTI-STRATEGY/
│   │── app.py                # Main Flask application
│   │── utils/
│   │   ├── datasets.py       # Dataset loading (TSP, Knapsack, Graph)
│   │   ├── bench.py          # Benchmarking functions
│   │── algorithms/
│   │   ├── greedy.py
│   │   ├── d_p.py
│   │   ├── backtracking.py
│   │   ├── branch_and_bound.py
│   │   ├── divide_and_conquer.py
│   │── templates/
│   │   ├── index.html        # UI
│   │── static/               # CSS, JS, assets
│   │── data/                 # Uploaded datasets
│   ├── requirements.txt      # Dependencies

⚙️ Installation
1️⃣ Clone Repository
git clone https://github.com/your-username/multi-strategy-optimization.git
cd multi-strategy-optimization/MULTI-STRATEGY

2️⃣ Install Dependencies

If internet access is allowed:

pip install -r requirements.txt


If internet is blocked (Nimbus case), upload the .whl files manually and install:

pip install package-name.whl

▶️ Usage

Run the Flask app:

python3 app.py


By default, the app will be available at:

http://127.0.0.1:5000/

📊 Example Problems
🧭 Traveling Salesman Problem (TSP)

Upload a set of coordinates (.csv)

Choose algorithm (Greedy / DP / Backtracking / Branch & Bound / Divide & Conquer)

Get best route, cost, and time

🎒 Knapsack Problem

Upload dataset with item values & weights

Choose algorithm (Greedy, DP, etc.)

Get selected items, max value, and computation time

🔗 Graph Matching

Upload a graph dataset (.json)

Solve maximum weight matching using NetworkX

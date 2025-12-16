# 🏬 Mall Exit Optimization using AI Search Algorithms

## 📌 Project Overview

This is a collaborative university project for the Artificial Intelligence course.
The project simulates a **shopping mall environment** where multiple autonomous robots attempt to reach an **exit point** using different AI search algorithms.

Each robot is programmed with a specific search strategy.
The algorithm that reaches the exit **faster and more efficiently** is selected as the best solution for real-world deployment.

---

## 🎯 Project Objective

* Apply and compare classical **AI search algorithms**
* Analyze performance based on:

  * Time to reach the exit
  * Path length
  * Optimality
* Determine the most efficient navigation strategy

---

## 🤖 Scenario Description

* The mall is represented as a **2D grid map**
* Obstacles represent walls, shops, or blocked paths
* All robots start from the same position
* Each robot runs **one search algorithm at a time**
* The robot that reaches the **exit point first** is considered the optimal solution

> ⚠ To ensure fair comparison, only **one agent is executed per run** (no collisions).

---

## 🧠 Implemented Search Algorithms

| Algorithm                        | Description                                     |
| -------------------------------- | ----------------------------------------------- |
| Breadth First Search (BFS)       | Finds shortest path in unweighted graphs        |
| Depth First Search (DFS)         | Explores depth-first paths                      |
| Iterative Deepening Search (IDS) | Combines DFS depth limits with BFS completeness |
| Uniform Cost Search (UCS)        | Finds the lowest cumulative cost path           |
| A* Search                        | Uses heuristic to optimize search               |
| Hill Climbing                    | Greedy local optimization search                |

---

## 🛠 Technologies Used

* **Python 3**
* Standard Python libraries
* Terminal-based simulation

---

## ▶ How to Run the Project

### 1️⃣ Clone the repository

```bash
git clone https://github.com/DevMohamedNasser/FireEscapeRouteRobot
cd ./Project
```

### 2️⃣ Install required libraries

pip3 install numpy matplotlib PyOpenGL PyOpenGL_accelerate
> Make sure Python 3 is installed on your system.

### 3️⃣ Run the program

python3 main.py <algorithm>

Replace <algorithm> with one of the following options:
| Algorithm Name             | Example Command             |
| -------------------------- | --------------------------- |
| Breadth First Search       | `python3 main.py bfs`       |
| Depth First Search         | `python3 main.py dfs`       |
| Iterative Deepening Search | `python3 main.py ids`       |
| Uniform Cost Search        | `python3 main.py ucs`       |
| A* Search                  | `python3 main.py astar`     |
| Hill Climbing              | `python3 main.py hillclimb` |

> ⚠ Note: Depending on your system configuration, you might need to run the commands with `python` or `python3`.  
> Example: `python main.py bfs` or `python3 main.py bfs`


---

## 👥 Team Members & Responsibilities

### 🔹 A* Search

* Mohamed Refat Mustafa Abd-Elmajid Nasser
* **ID:** 2023176

---

### 🔹 Iterative Deepening Search (IDS)

* Mohamed Khaled El-Daheesh Ahmed
* **ID:** 2023174

---

### 🔹 Breadth First Search (BFS)

* Mohamed Elsayed Mohamed Ahmed Aboelsoud
* **ID:** 2023168

---

### 🔹 Project Management

* Maram Hazem Fouad Ismail Ahmed
*  **ID:** 2023202

---

### 🔹 Hill Climbing Search

* Menna Ahmed Ibrahim Agamy
*  **ID:** 2023222

---

### 🔹 Uniform Cost Search (UCS)

* Heba Ahmed Ibrahim Agamy
*  **ID:** 2023244

---

### 🔹 Depth First Search (DFS)

* Wessam Mohamed El-Sayed Al-Hanafy
* **ID:** 2023249

---

## 📊 Evaluation Criteria

* Path length
* Execution time
* Search optimality
* Algorithm efficiency

---

## 🚀 Future Enhancements

* Visual simulation using Pygame
* Dynamic obstacles
* Multi-agent environment
* Performance comparison charts

---

## 📜 License

This project is developed for educational purposes only.

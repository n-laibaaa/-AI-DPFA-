# ✨ DPFA ✨
------------------------------------------------------------------------

## 🚀 Features

-   A\* Search (f(n) = g(n) + h(n))
-   Greedy Best-First Search (f(n) = h(n))
-   Manhattan & Euclidean heuristics
-   Dynamic obstacle spawning
-   Real-time path re-planning
-   Interactive Tkinter GUI
-   Live performance metrics:
    -   Nodes Expanded
    -   Path Cost
    -   Execution Time

------------------------------------------------------------------------

## 🎨 Visualization

The GUI uses a custom pastel colour palette:

-   🟣 Obstacles\
-   🟡 Frontier Nodes\
-   🔵 Visited Nodes\
-   🟢 Final Path\
-   🔴 Goal Node

------------------------------------------------------------------------

## 🛠 Installation

Make sure Python 3.10+ is installed.

No external libraries are required (uses built-in Tkinter).

Run the program:

``` bash
python your_file_name.py
```

------------------------------------------------------------------------

## 🧠 Algorithms

### A\* Search

Uses: f(n) = g(n) + h(n)

Guarantees an optimal path with an admissible heuristic.

### Greedy Best-First Search

Uses: f(n) = h(n)

Faster in simple environments but does not guarantee an optimal path.

------------------------------------------------------------------------

## 📊 Experimental Analysis

Performance comparison was conducted under: - Low obstacle density (Best
Case) - High obstacle density (Worst Case)

Metrics analysed: - Nodes Expanded - Path Cost - Execution Time

------------------------------------------------------------------------

## 📁 Project Structure

    dpf.py
    README.md
    Report.pdf

------------------------------------------------------------------------

## 📌 Course Information

Artificial Intelligence\
Project: DPFA

------------------------------------------------------------------------

Built with logic, algorithms, and aesthetic energy ✨

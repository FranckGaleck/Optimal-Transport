# 🚚 Optimal Transport (Discrete) – 2D Point Matching

This project explores the discrete form of **Optimal Transport** (OT) through 2D point distributions.  
It formulates and solves a transport problem using linear programming, and visualizes the resulting transport plan.

---

## 🧠 What is Optimal Transport?

Optimal Transport seeks the most cost-efficient way to move mass from one distribution to another.  
This project works with **finite distributions of points**, and minimizes the total transport cost.

---

## 📊 What’s Implemented

✔️ **Custom 2D distributions** (`mu` and `nu`)  
✔️ **Pairwise cost matrix** using squared Euclidean distances  
✔️ **Optimization via linear programming** (`scipy.optimize.linprog`)  
✔️ **Transport plan** $\gamma$ matrix computation  
✔️ **Graphical visualization** of transport flows between points  
✔️ **Calculation of total transport cost** (Wasserstein distance in discrete form)

---

# 🚚 Vehicle Routing Problem Solver (VRP)

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![Tkinter](https://img.shields.io/badge/UI-Tkinter-green.svg)
![Algorithm](https://img.shields.io/badge/Algorithm-Genetic%20Algorithm-orange.svg)
![License](https://img.shields.io/badge/License-MIT-brightgreen.svg)

A **Python-based Vehicle Routing Problem (VRP) Solver** using a **Genetic Algorithm**, featuring an **interactive and visually rich Tkinter GUI** for route visualization and analysis.

This project is designed for **academic use, hackathons, and optimization research**, offering an intuitive interface and clear route summaries.

---

## 🖼️ User Interface Preview

> 📌 *Replace the image paths below with actual screenshots from your application.*

### Main Application Window
![Main UI](assets/ui_main.png)

### Route Visualization
![Route Visualization](assets/ui_routes.png)

### Control & Information Panel
![Info Panel](assets/ui_info.png)

---

## ✨ Features

- 🧠 Genetic Algorithm–based route optimization  
- 🗺️ Interactive Tkinter canvas visualization  
- 🏭 Automatic depot identification  
- ➕ Add delivery locations dynamically  
- ➖ Delete locations using dropdown selection  
- 🚛 Multi-vehicle route planning  
- 🎨 Color-coded vehicle routes  
- 📋 Text-based route summary panel  

---

## 🧩 Project Structure

```
VRP-Solver/
├── main.py                  # Tkinter GUI application (VRPSolver)
├── location.py              # Location model & drawing utilities
├── Chromosome.py              # Forming parents & Child Node
├── .py    
├── genetic_algorithm.py     # Genetic Algorithm implementation
├── assets/                  # UI screenshots & icons
│   ├── ui_main.png
│   ├── ui_routes.png
│   └── ui_info.png
├── README.md                # Project documentation
```

---

## ⚙️ Requirements

- Python **3.8+**
- Built-in Python libraries only:
  - `tkinter`
  - `random`

✅ No external dependencies required.

---

## ▶️ How to Run

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/vrp-solver.git
cd vrp-solver
```

### 2️⃣ Run the Application
```bash
python main.py
```

---

## 🧭 Application Workflow

### 🔹 Initial Setup
- The **first generated location** is treated as the **depot**
- Random locations are auto-generated for quick testing

### ➕ Adding a Location
- Enter **X coordinate** (0–49)
- Enter **Y coordinate** (0–29)
- Click **Add Location**

### ➖ Deleting a Location
- Select a location from the dropdown
- Click **Delete**

### 🚀 Solving the VRP
- Enter the **number of vehicles**
- Click **Solve**
- Optimized routes are displayed using **distinct colors**

---

## 🧬 Genetic Algorithm Overview

- Locations are divided among vehicles
- Each vehicle route is optimized independently
- Core GA operations:
  - Population initialization
  - Fitness evaluation (distance minimization)
  - Selection
  - Crossover
  - Mutation
- Best chromosome from the final generation is selected as the optimal route

---

## 📊 Output

### 🖼️ Visual Output
- Nodes represent locations
- Lines represent optimized routes
- Each vehicle has a unique color

### 📝 Text Output
- Vehicle-wise route sequence
- Displayed in the **Information Panel**

---

## ⚠️ Limitations

- No vehicle capacity constraints
- Equal distribution of locations among vehicles
- Not suitable for very large datasets
- Uses synthetic coordinate data only

---

## 🚀 Future Enhancements

- Vehicle capacity and demand constraints
- Distance matrix & real-world coordinates
- Google Maps / OpenStreetMap integration
- True multi-vehicle GA optimization
- Export routes to CSV / JSON
- Performance optimization for large-scale VRP

---

## 👨‍💻 Author

**Sivaprakash**

**Domains:**
- Artificial Intelligence  
- Machine Learning  
- Optimization Algorithms  
- Intelligent Transportation Systems  

---

## 📄 License

This project is licensed under the **MIT License**.

---

⭐ If you find this project useful, consider starring the repository!

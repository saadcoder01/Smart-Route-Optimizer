# Smart-Route-Optimizer
User Driven Route Optimizer

# 📍 Smart Route Navigation System

This is a console-based **Smart Route Finder and Optimizer**, created using C++ with Object-Oriented Programming (OOP) principles. It helps users find the most efficient travel route between two locations, considering factors like traffic, u-turns, distance, and construction.

---

## 🚀 Features

- **Multiple Travel Modes**: Choose between walking, biking, or driving.
- **Route Details**: Each segment includes distance, u-turn count, traffic level, and construction status.
- **Smart Recommendation**: Suggests best route based on travel time and road conditions.
- **Traffic-Aware Estimates**: Travel time changes based on traffic level.
- **Construction Handling**: Tries to avoid construction zones unless they save significant time.
- **Top 2 Routes**: Displays the two fastest routes available.
- **User-Friendly Input**: Clearly labeled options and robust validation for beginners.

---

## 🧠 How It Works

1. Predefined locations and routes are set in the program.
2. The user chooses a start and destination.
3. User selects a travel mode.
4. The system finds **all possible routes** using Depth-First Search (DFS).
5. Calculates time, distance, and evaluates construction impact.
6. Displays:
   - Two fastest routes
   - One recommended route (either fastest or no-construction, if reasonable)

---

## ⚙️ Technologies Used

- **Programming Language**: C++
- **Key Concepts**:
  - Classes & Objects
  - Enums
  - Vectors
  - DFS Algorithm
  - Conditional Logic & Filtering

---

## 📦 How to Run

1. Compile using any modern C++ compiler:
   ```bash
   g++ -o RouteFinder main.cpp
   ```

2. Run the application:
   ```bash
   ./RouteFinder
   ```

3. Follow the prompts to explore routes.

---

## 📂 Suggested Repository Name

Here are some suitable names for your GitHub repository:

- `SmartRouteFinder-OOP`
- `RoutePlannerCPP`
- `UrbanNavigator`
- `PathOptimizerCPlusPlus`

---

## ✅ Perfect For

- Beginners learning OOP and C++
- Those exploring graph traversal (DFS)
- Mini-projects with real-world use cases

---

Enjoy navigating smartly! 🌐

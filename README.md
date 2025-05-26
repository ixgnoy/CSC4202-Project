# 🍔 Food Delivery Optimization System

*Java-based algorithmic solution to prioritize food orders and find the most efficient delivery routes.*

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Project Status](https://img.shields.io/badge/status-Completed-brightgreen?style=for-the-badge)
![Lines of Code](https://img.shields.io/tokei/lines/github/ixgnoy/CSC3402-Project?style=for-the-badge)
![Last Commit](https://img.shields.io/github/last-commit/ixgnoy/CSC3402-Project?style=for-the-badge)
![Visitors](https://visitor-badge.laobi.icu/badge?page_id=ixgnoy.CSC3402-Project)

---

## 🗂 Table of Contents

### 📖 Part 1 – Introduction
- 1.0 Scenario and Problem  
- 2.0 Importance of Optimal Solution  
- 3.0 Algorithm Suitability Review  

### 🧠 Part 2 – Algorithm Design
- 4.0 Model Development of the Scenario  
  - 4.1 Overview  
  - 4.2 Delivery Prioritization for Food Orders  
  - 4.3 Best Travelling Route  
  - 4.4 Constraints and Challenges  
- 5.0 Algorithm Design  
  - 5.1 Overview  
  - 5.2 Delivery Prioritization for Food Orders  
  - 5.3 Best Travelling Route  
  - 5.4 Example  
- 6.0 Algorithm Specification  

### 💻 Part 3 – Implementation of Algorithm
- [7.0 Coding](part_3_implementation/7.0-coding)  
- 7.1 Algorithm Implementations  
- 7.2 Algorithm Descriptions  
- 7.3 Demonstration  
- 7.4 Results  
- 7.5 Analysis of Algorithms  
  - 7.5.1 Correctness of the Algorithm  
  - 7.5.2 Time Complexity Analysis  

---

## 🧰 Tech Stack

- ![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
- Algorithm Design
- Problem Solving
- Time & Space Complexity Analysis

---

### ✍️ Notes
This project focuses on building **an optimal food delivery algorithm** using Java. It simulates order prioritization, route efficiency, and applies time complexity analysis for benchmarking algorithm performance.

---

### 🚀 How to Run
```bash
javac FoodDelivery.java
java FoodDelivery
```

  ## Table of Contents
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

</head>
<body>
  <hr>
  <h2><a href="https://github.com/ixgnoy/CSC4202-Project/blob/main/part_1_introduction/README.md">Part 1 – Introduction</a></h2>
  <ul>
    <li><a href="https://github.com/ixgnoy/CSC4202-Project/blob/main/part_1_introduction/1_Scenario_and_Problem.md">1.0 Scenario and Problem</a></li>
    <li><a href="https://github.com/ixgnoy/CSC4202-Project/blob/main/part_1_introduction/2_importance_of_optimal_solution.md">2.0 Importance of Optimal Solution</a></li>
    <li><a href="https://github.com/ixgnoy/CSC4202-Project/blob/main/part_1_introduction/3_algorithms_suitability_review.md">3.0 Algorithm Suitability Review</a></li>
  </ul>
  <h2><a href="https://github.com/ixgnoy/CSC4202-Project/blob/main/part_2_algorithm_design/README.md">Part 2 – Algorithm Design</a></h2>
  <ul>
    <li><a href="https://github.com/ixgnoy/CSC4202-Project/blob/main/part_2_algorithm_design/4_scenario_model_development/README.md">4.0 Model Development of the Scenario</a></li>
      <ul>
        <li><a href="https://github.com/ixgnoy/CSC4202-Project/blob/main/part_2_algorithm_design/4_scenario_model_development/4.1_overview.md">4.1 Overview</a></li>
        <li><a href="https://github.com/ixgnoy/CSC4202-Project/blob/main/part_2_algorithm_design/4_scenario_model_development/4.2-delivery-prioritization-for-food-orders.md">4.2 Delivery Prioritization for Food Orders</a></li>
        <li><a href="https://github.com/ixgnoy/CSC4202-Project/blob/main/part_2_algorithm_design/4_scenario_model_development/4.3_best_travelling_route.md">4.3 Best Travelling Route</a></li>
        <li><a href="https://github.com/ixgnoy/CSC4202-Project/blob/main/part_2_algorithm_design/4_scenario_model_development/4.4_constrain_and_challenges.md">4.4 Constraints and Challenges</a></li>
      </ul>
    </li>
    <li><a href="https://github.com/ixgnoy/CSC4202-Project/blob/main/part_2_algorithm_design/5_algorithm_design/README.md">5.0 Algorithm Design</a></li>
      <ul>
        <li><a href="https://github.com/ixgnoy/CSC4202-Project/blob/main/part_2_algorithm_design/5_algorithm_design/5.1_overview.md">5.1 Overview</a></li>
        <li><a href="https://github.com/ixgnoy/CSC4202-Project/blob/main/part_2_algorithm_design/5_algorithm_design/5.2_delivery_prioritization_for_food_orders.md">5.2 Delivery Prioritization for Food Orders</a></li>
        <li><a href="https://github.com/ixgnoy/CSC4202-Project/blob/main/part_2_algorithm_design/5_algorithm_design/5.3_best_travelling_route.md">5.3 Best Travelling Route</a></li>
        <li><a href="https://github.com/ixgnoy/CSC4202-Project/blob/main/part_2_algorithm_design/5_algorithm_design/5.4_example.md">5.4 Example</a></li>
      </ul>
    </li>
    <li><a href="https://github.com/ixgnoy/CSC4202-Project/tree/main/part_2_algorithm_design/6_Algorithm_Specification">6.0 Algorithm Specification</a></li>
  </ul>
  <h2><a href="https://github.com/ixgnoy/CSC4202-Project/blob/main/part_3_implementation/README.md">Part 3 – Implementation of Algorithm</a></h2>
  <ul>
    <li><a href="https://github.com/ixgnoy/CSC4202-Project/tree/main/part_3_implementation/7.0-coding">7.0 Coding</a></li>
      <ul>
        <li><a href="https://github.com/ixgnoy/CSC4202-Project/blob/main/part_3_implementation/7.0-coding/7.1-algorithm-implementations.md">7.1 Algorithm Implementations</a></li>
        <li><a href="https://github.com/ixgnoy/CSC4202-Project/blob/main/part_3_implementation/7.0-coding/7.2-algorithm-descriptions.md">7.2 Algorithm Descriptions</a></li>
        <li><a href="https://github.com/ixgnoy/CSC4202-Project/blob/main/part_3_implementation/7.0-coding/7.3-demonstration.md">7.3 Demonstration</a></li>
        <li><a href="https://github.com/ixgnoy/CSC4202-Project/blob/main/part_3_implementation/7.0-coding/7.4-results.md">7.4 Results</a></li>
        <li><a href="https://github.com/ixgnoy/CSC4202-Project/tree/main/part_3_implementation/7.0-coding/7.5-analysis-of-algorithm">7.5 Analysis of Algorithms</a></li>
        <ul>
          <li><a href="https://github.com/ixgnoy/CSC4202-Project/blob/main/part_3_implementation/7.0-coding/7.5-analysis-of-algorithm/7.5.1-correctness-of-the-algorithm.md">7.5.1 Correctness of the Algorithm</a></li>
          <li><a href="https://github.com/ixgnoy/CSC4202-Project/blob/main/part_3_implementation/7.0-coding/7.5-analysis-of-algorithm/7.5.2-time-complexity-analysis.md">7.5.2 Time Complexity Analysis</a></li>
        </ul>
      </ul>
    </li>
</body>
</html>


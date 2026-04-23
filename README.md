#  Monte Carlo Simulation to Estimate Value of Pi

##  Overview
This project uses a **Monte Carlo Simulation** technique to estimate the value of π (pi) using random sampling.

The idea is based on probability and geometry — by randomly placing points inside a square and checking how many fall inside an inscribed circle, we can approximate the value of π.

---

##  Mathematical Concept

We consider:

- A square of side `2r`
- A circle of radius `r` inside the square

### Step 1: Area Ratio

πr² / 4r² = (points in circle) / (points in square)

### Step 2: Simplified Formula

π = 4 × (points in circle / points in square)

---

##  How It Works

1. Generate random (x, y) points between -1 and 1  
2. Check if the point lies inside the circle using:

x² + y² ≤ 1

3. Count:
- Points inside the circle  
- Total points  
4. Use the formula to estimate π  

---

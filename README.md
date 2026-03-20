# 📘 CS5710 – Machine Learning  
## 🧠 Home Assignment 3

---

## 👤 Student Information
- **Name:** Bala Aravind Nali  
- **Student ID:** 700791579  
- **Course:** CS5710 – Machine Learning  

---

## 📌 Overview
This assignment covers:
- Neural Networks (Feedforward & Multi-layer)  
- XOR with ReLU  
- Perceptron Decision Boundary  
- Linear & Nonlinear SVM  
- PCA and theoretical concepts  

---

# 🔹 Part A: Calculations

---

## ✅ Q1. Multi-Input Feedforward

### Input
x = (2, 1, 3)
x' = (2, 1, 3, 1)
### Weights
A = [[0.2, -0.5],
[0.1, 0.3],
[-0.2, 0.8],
[0.4, -0.6]]
B = (0.7, -1.2, 0.5)

### Hidden Layer
z1 = 0.3
z2 = 1.1

### Activation
h1 ≈ 0.574
h2 ≈ 0.750

### Output
z = 0.0018
y ≈ 0.5004

---

## ✅ Q2. XOR with ReLU

### Model
h1 = ReLU(x1 + x2)
h2 = ReLU(x1 + x2 - 1)
h3 = ReLU(x2 - x1)
y = ReLU(h1 - 2h2 + h3)

### Results

| Input | Output |
|------|--------|
| (0,0) | 0 |
| (0,1) | 2 |
| (1,0) | 1 |
| (1,1) | 0 |

### Conclusion
- Does not perfectly compute XOR  
- Output is not strictly binary  

---

## ✅ Q3. Decision Boundary

### Equation
x1 - 2x2 + 1 = 0
x2 = (x1 + 1)/2

### Diagram
![Q3 Decision Boundary]

### Classification

| Point | Prediction |
|------|-----------|
| (2,1) | 1 |
| (1,3) | 0 |
| (3,2) | 1 |
| (0,1) | 0 |

---

## ✅ Q4. Multi-Layer Forward Pass

### Input
x = (1, -1)

### Layer 1
h ≈ (0.574, 0.269)

### Layer 2
h ≈ (0.610, 0.548)

### Output
y ≈ 0.636

---

## ✅ Q5. Linear SVM

### Solution
α1 = 0
α2 = 0.25
α3 = 0.25

### Weights & Bias
w = (0.5, 0.5)
b = -1

### Hyperplane
x1 + x2 = 2

## ✅ Q6. Nonlinear SVM

### Mapping
φ(x1,x2) = (x1², x2², √2·x1x2)

### Transformed Points
(1,0) → (1,0,0)
(2,1) → (4,1,2√2)

### Decision Function
f(x) = w1x1² + w2x2² + √2 w3 x1x2 + b

### Classification
q = (1,1)
φ(q) = (1,1,√2)

---

# 🔹 Part B: Theory

---

## ✅ Q1. Neural Networks Basics
- Neuron: processing unit  
- Synapse: connection weight  
- Activation: introduces non-linearity  
- DAG ensures no cycles and efficient computation  

---

## ✅ Q2. Architecture
- Depth: number of layers  
- Width: neurons per layer  
- Universal approximation: NN approximates any function  

---

## ✅ Q3. Perceptron vs SVM
- Perceptron: minimize error  
- SVM: maximize margin  
- SVM generalizes better  

---

## ✅ Q4. Margins
- Margin = distance to boundary  
- Support vectors define boundary  
- Larger margin improves robustness  

---

## ✅ Q5. PCA
- Captures maximum variance  
- Requires centered data  
- Eigenvalues represent importance  

---

## ✅ Q6. PCA vs Random Projection
- PCA: optimal but computationally expensive  
- Random projection: faster but approximate  


## Repository
- Assignment uploaded to GitHub  
- Proper structure maintained  

# 🚀 Final Notes
- All solutions are clearly explained  
- Step-by-step approach followed  


# Cubic Equation Solver using PyTorch

## 📌 Overview
This project demonstrates solving a cubic equation of the form:

ax³ + bx² + cx + d = 0

using **PyTorch** and **Stochastic Gradient Descent (SGD)**.  
Instead of using symbolic math, the problem is treated as an optimization task
where gradient descent is used to approximate a solution.

---

## 🎯 Objective
To build a simple cubic equation solver using:
- PyTorch
- Stochastic Gradient Descent (SGD)
- Rectified Linear Unit (ReLU) activation

This project is part of an introductory AI / Machine Learning task.

---

## 🧠 Approach
- The variable `x` is initialized as a trainable tensor.
- The cubic equation is converted into a loss function.
- ReLU activation is applied to ensure non-negative loss.
- SGD optimizer is used to minimize the loss.
- After training, the optimized value of `x` represents an approximate solution
  to the cubic equation.

---

## ⚙️ Tools & Libraries Used
- Python
- PyTorch
- Google Colab

---

## ▶️ How to Run
1. Open the notebook in **Google Colab**
2. Run all cells from top to bottom
3. Observe the loss reduction during training
4. View the final approximated solution for `x`

---

## 📊 Output
- Training progress showing loss reduction
- Final approximated value of `x` that satisfies the cubic equation

---

## 📚 Learning Outcome
- Understanding gradient descent optimization
- Applying SGD in PyTorch
- Using ReLU activation
- Treating mathematical equations as optimization problems

---

## 🏁 Conclusion
This project showcases how neural network optimization techniques can be applied
to solve mathematical equations using PyTorch, providing a strong foundation
for understanding gradient-based learning.

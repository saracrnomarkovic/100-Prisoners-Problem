# 🔐 The 100 Prisoners Problem

A mathematical and computational study of the famous "100 Prisoners and 100 Boxes" problem using probability theory, combinatorics, permutation cycles, asymptotic analysis, and large-scale Monte Carlo simulations.

The project combines rigorous mathematical reasoning with experimental verification through Python simulations.

---

## 🎯 Project Objectives

The primary goal of this project is to understand why a problem that appears almost impossible at first glance has a surprisingly high probability of success.

The project investigates:

- Random search strategies
- Sequential box-opening strategies
- Block-based strategies
- Cycle-following strategies
- Experimental search for alternative strategies
- Asymptotic behavior as the number of prisoners grows
- Cycle structures of random permutations

---

## 🧠 Mathematical Background

The problem lies at the intersection of several mathematical fields:

- Probability Theory
- Combinatorics
- Permutations
- Cycle Decomposition
- Asymptotic Analysis
- Discrete Mathematics

A key insight is that the optimal strategy transforms the problem into the study of cycle lengths in random permutations.

---

## 🔍 Research Questions

The project explores several questions:

- Why does the cycle-following strategy outperform random guessing?
- How do cycle lengths influence success probability?
- Can alternative strategies outperform cycle-following?
- What happens when the number of prisoners becomes very large?
- Why does the success probability converge to a constant value?

---

## 📐 Theoretical Analysis

The mathematical report includes:

- Formal problem definition
- Derivation of success probabilities
- Analysis of permutation cycles
- Proofs involving cycle decomposition
- Asymptotic arguments
- Convergence analysis

One of the main theoretical results is that the probability of success converges to:

```
1 - ln(2)
```

which is approximately:

```
30.685%
```

---

## 🧪 Simulation Study

Extensive Monte Carlo simulations were implemented in Python to experimentally verify the theoretical results.

The simulations include:

- Random strategy evaluation
- Sequential search strategies
- Block strategies
- Cycle-following strategy
- Comparative performance analysis
- Large-scale repeated experiments

Simulation results consistently confirm the theoretical success probability of approximately:

**31%**

for the cycle-following strategy.

---

## 📊 Key Findings

✅ Random guessing performs extremely poorly.

✅ The cycle-following strategy dramatically increases success probability.

✅ Success depends entirely on the maximum cycle length of the underlying permutation.

✅ Experimental results closely match theoretical predictions.

✅ The asymptotic probability converges to approximately:

```
1 - ln(2)
```

---

## 📂 Repository Structure

### Strategy simulations.ipynb

Contains:

- Monte Carlo simulations
- Strategy comparisons
- Numerical experiments
- Visualizations
- Empirical validation of theoretical results

### Mathematical aspects of strategies.pdf

Contains:

- Mathematical derivations
- Probability calculations
- Cycle analysis
- Asymptotic arguments
- Interpretation of simulation results

---

## ⚙️ Technologies

- Python
- NumPy
- Matplotlib
- Jupyter Notebook

---

## 📚 Topics

Probability Theory • Combinatorics • Permutations • Cycle Decomposition • Monte Carlo Simulation • Experimental Mathematics • Algorithms • Discrete Mathematics

---

## 👩‍💻 Author

Sara Crnomarkovic

Faculty of Mathematics, University of Belgrade

📧 sara.crnomarkovic2002@gmail.com

🔗 LinkedIn: https://www.linkedin.com/in/saracrnomarkovic/

🔗 GitHub: https://github.com/saracrnomarkovic

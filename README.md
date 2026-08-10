# 5.1 — Nonlinear Sigmoidal Hashimoto Dynamics (Julia)

A nonlinear extension of 5.0 introducing **sigmoidal update rules**, **Jacobian stability**, **fixed points**, and **limit cycles** for non‑backtracking operators.

---

## Hypothesis Framework

### **1. Research Hypothesis (H₁)**  
Introducing **sigmoidal nonlinearities** into the Hashimoto operator produces **stable nonlinear dynamical regimes**—including fixed points and limit cycles—that correlate with underlying graph structure and differ predictably from linear spectral behavior.

This asserts that nonlinear propagation reveals richer dynamical structure than linear Hashimoto walks.

---

### **2. Null Hypothesis (H₀)**  
Nonlinear sigmoidal updates produce **no meaningful dynamical differences** from linear Hashimoto propagation; fixed points, cycles, and stability characteristics are statistically equivalent.

---

### **3. Alternative Hypothesis (H₂)**  
Nonlinear sigmoidal dynamics destabilize non‑backtracking propagation, producing chaotic trajectories, unstable Jacobians, or non‑interpretable limit cycles.

---

## 4. Variables

### **Independent Variables**
- Sigmoid type (logistic, tanh, softsign)  
- Nonlinearity strength  
- Graph structure (n = 6)  

### **Dependent Variables**
- Fixed point existence  
- Limit cycle formation  
- Jacobian eigenvalues  
- Stability basin size  

### **Controlled Variables**
- Initial conditions  
- Numerical precision  
- Sigmoid parameterization  

---

## 5. Experimental Method

1. Define nonlinear Hashimoto update rule:  
   \[
   x_{t+1} = \sigma(Bx_t)
   \]
   where \( B \) is the Hashimoto operator and \( \sigma \) is a sigmoid.

2. Compute fixed points via iterative convergence and root‑finding.  
3. Analyze Jacobian at fixed points:  
   \[
   J = \sigma'(Bx^*) B
   \]
4. Detect limit cycles using Poincaré sections and recurrence plots.  
5. Compare nonlinear dynamics to linear spectral predictions.

---

## 6. Evaluation Metrics

- Fixed point stability (Jacobian spectral radius)  
- Limit cycle period and amplitude  
- Nonlinear propagation entropy  
- Divergence rate under perturbation  

---

## 7. Interpretation Criteria

- **Support for H₁:** Stable fixed points or structured limit cycles emerge.  
- **Support for H₂:** Nonlinearities induce chaotic or divergent behavior.  
- **Support for H₀:** Dynamics mirror linear Hashimoto behavior.

---

## 8. Extensions

- **Sigmoid operators**  
- **Jacobian stability**  
- **Limit cycle detection**  
- **Nonlinear dynamical systems**  

---

**Contributions are off**

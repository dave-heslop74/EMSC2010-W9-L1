# EMSC2010 – Week 9 Lectorial 1: Dynamical Systems and Chaos

This repository contains the template Jupyter notebooks for **Week 9 Lectorial 1** of *EMSC2010: Data Science for Earth System Scientists* at the Australian National University.

The session introduces **numerical models** — mathematical models that describe can be applied to two classic Earth and environmental science problems: planetary energy balance and population dynamics.

---

## Notebooks

### Notebook 1 – Zero-Dimensional Energy Balance Model (`NB1`)

This notebook models Earth's surface temperature using a zero-dimensional energy balance model with no atmosphere. Students implement and evaluate the equation:

$$T_e = \left[\frac{S}{4\alpha}(1-A)\right]^{1/4}$$

where $T_e$ is Earth's equilibrium surface temperature, $S$ is the solar flux (1366 W/m²), $A$ is albedo (~0.3), and $\alpha$ is the Stefan–Boltzmann constant (5.67×10⁻⁸ W/m²/K⁴).

**Key concepts:** Radiative energy balance, Stefan–Boltzmann law, albedo, equilibrium temperature

**Libraries:** `numpy`, `matplotlib`

---

### Notebook 2 – The Logistic Population Model and Chaos (`NB2`)

This notebook explores population dynamics through three progressively more complex versions of the logistic model:

1. **Basic logistic model** — models year-on-year population change as a function of reproductive rate $a$ and current population size $x$:

$$x_{\text{next}} = a \, x_{\text{initial}}(1 - x_{\text{initial}})$$

2. **Logistic model with harvesting** — extends the model to include a harvest term $h$, exploring how resource extraction affects long-term population stability.

3. **Logistic model with randomness** — introduces environmental stochasticity by adding a normally distributed random term $r$ to the reproductive rate each year, simulating real-world variability.

4. **The logistic map** — sweeps over a wide range of reproductive rates and starting populations to reveal how ordered population cycles give way to unpredictable chaotic behaviour.

**Key concepts:** Dynamical systems, logistic growth, sensitivity to initial conditions

**Libraries:** `numpy`, `matplotlib`

---

## Getting Started

This is a **template repository**. To begin working on the notebooks:

1. Click **"Use this template"** at the top of this page to create a copy of the repository in your own GitHub account.
2. Open any notebook from your copy of the repository and click the **"Open in Colab"** badge at the top of the notebook to launch it in Google Colab.
3. Before submitting, replace the `uXXXXXXX` placeholder in the filename with your ANU student UID.

---

## Repository Structure

```
EMSC2010-W9-L1/
├── EMSC2010_W9_L1_NB1_uXXXXXXX.ipynb   # Zero-dimensional energy balance model
├── EMSC2010_W9_L1_NB2_uXXXXXXX.ipynb   # Logistic population model
├── LICENSE
└── README.md
```

---

## Course Information

| | |
|---|---|
| **Course** | EMSC2010 – Data Science for Earth System Scientists |
| **Institution** | Australian National University (ANU) |
| **Week** | 9 |
| **Session** | Lectorial 1 |
| **Topic** | Numerical modelling |

---

## License

This repository is released under the [MIT License](LICENSE).

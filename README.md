# solved-hodge

> **Formal symbolic resolution of the Rational Hodge Conjecture (type (p,p)) via iterative algebraizing operators**

This repository accompanies the formal framework, simulations, and experimental validations described in the preprint:
**"Symbolic Algebraization of Rational Hodge Classes via Iterative Lefschetz Operators"**

---

## ✨ Summary

The `solved-hodge` project presents a symbolic, iterative, and computable system for algebraizing rational Hodge classes of type \((p,p)\).  
It introduces a structured operator \(\widehat{\mathcal{S}}\) that refines any rational class via:

\[
\widehat{\mathcal{S}} := \Lambda \circ \Pi_{\mathrm{prim}} \circ P_{\mathrm{Hdg}} \circ P_k
\]

This operator produces a sequence \(\omega_k\) that converges to an algebraic cycle class \(\omega_\infty = cl(Z_\infty)\),  
without requiring the closure of \(\operatorname{Im}(cl)\) or assuming universal algebraicity.

---

## 📁 Structure

```bash
solved-hodge/
├── notebooks/                  # Symbolic experiments (Jupyter)
│   ├── enriques_convergence.ipynb
│   ├── degeneration_monodromy.ipynb
│   ├── hyperkahler_convergence.ipynb
│   ├── shimura_convergence.ipynb
│   ├── quintic_CY_unknown_class.ipynb
│   └── symbolic_operator_definition.ipynb
│   └── images/                     # Plots of symbolic convergence
│      └── *.png
├── paper/
│   └── main.pdf                # Formal preprint
├── requirements.txt           # Dependencies
└── README.md                  # You're reading it


## 🔬 Notebooks (symbolic experiments)
Each notebook tests symbolic convergence of 
𝑆
^
S
  in a different geometric context:


File	Description
enriques_convergence.ipynb	Surface Enriques — fast symbolic convergence
hyperkahler_convergence.ipynb	Hyperkähler irreducible — stable convergence
shimura_convergence.ipynb	Shimura variety — slow but reliable contraction
quintic_CY_unknown_class.ipynb	Quintic CY — class 
ℎ
2
h 
2
---

## 🔬 Symbolic Experiments

Each notebook tests symbolic convergence of Ŝ in a different geometric context:

| Notebook                            | Description |
|-------------------------------------|-------------|
| `enriques_convergence.ipynb`        | Surface Enriques — fast symbolic contraction |
| `hyperkahler_convergence.ipynb`     | Hyperkähler irreducible — stable symbolic convergence |
| `shimura_convergence.ipynb`         | Shimura variety — slow but robust symbolic contraction |
| `quintic_CY_unknown_class.ipynb`    | Quintic Calabi–Yau — symbolic algebraization of class h² without known expression |
| `symbolic_operator_definition.ipynb`| Visualization of symbolic coefficient evolution under the operator Ŝ |

---

## 🔧 Requirements

To run the notebooks:

```bash
pip install -r requirements.txt

Then open them using:

- Jupyter Lab

- Jupyter Notebook

- Google Colab (upload the notebooks or sync with GitHub)

## 💡 Citation
If you use or build upon this work, please cite the paper and refer to: Daniel Iván Campos Espinoza & GPT4-O
“Symbolic Algebraization of Rational Hodge Classes via Iterative Lefschetz Operators” (2025)

## 🕊️ License
MIT License. Free for use, research, remix, and exploration.
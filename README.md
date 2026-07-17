# Topology Study Notes & Solutions

This repository serves as a personal archive of my self-study journey in topology, focusing on point-set and algebraic topology. It contains rigorous, independently written proofs for various textbook exercises.

## Contents

- **[GTM_202_chapter_11.pdf](./GTM_202_chapter_11.pdf)**: Compiled PDF of the solutions, available for direct online reading.
- **[GTM_202_chapter_11.tex](./GTM_202_chapter_11.tex)**: Full LaTeX source code.

## Selected Solved Problems

### Topological Properties under Covering Maps
- **Problem 11-1**: Topological properties inheritance under covering maps $q: E \to X$:
  - **(a)** If $X$ is Hausdorff, then $E$ is Hausdorff.
  - **(b)** If $X$ is an $n$-manifold, then $E$ is an $n$-manifold.
  - **(c)** If $E$ is an $n$-manifold and $X$ is Hausdorff, then $X$ is an $n$-manifold.

### Concrete Covering Space Examples
- **Problem 11-2**: A rigorous proof that the natural projection $q: S^n \to \mathbb{R}P^n$ is a two-sheeted covering map for any $n \ge 1$.
- **Problem 11-3**: Analysis of the Riemann surface model $S = \{(z, w) \in \mathbb{C}^2 : w^2 = z, w \neq 0\}$. Show that the coordinate projection $\pi_1: \mathbb{C}^2 \to \mathbb{C}$ restricts to a two-sheeted covering map $q: S \to \mathbb{C} \setminus \{0\}$.

### Compactness and Proper Maps
- **Problem 11-10**: A covering map is proper if and only if it is a finite-sheeted covering.
- **Problem 11-11**: The total space $E$ of a covering is compact if and only if the base space $X$ is compact and the covering is finite-sheeted.
- **Double Cover of the Klein Bottle**: A rigorous proof of the two-sheeted covering of the Klein bottle by the 2-torus, utilizing coset decompositions and quotient topologies.

## Compilation Details

- **Compiler**: XeLaTeX / PDFLaTeX
- **Packages Used**: `amsmath`, `amssymb`, `amsthm`, `geometry`, `enumerate`

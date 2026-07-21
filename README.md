# Topology Study Notes & Solutions

An archive of exercise solutions and proofs from my journey learning topology. Uploaded here for personal backup and progress tracking.

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
- **Problem 11-2**: A proof that for any $n \geq 1$, the map $q: S^n \to \mathbb{P}^n$ defined by sending each point $x \in S^n$ to the line through the origin and $x$ is a covering map. 
- **Problem 11-3**: Analysis of the Riemann surface model $S = \{(z, w) \in \mathbb{C}^2 : w^2 = z, w \neq 0\}$. Show that the coordinate projection $\pi_1: \mathbb{C}^2 \to \mathbb{C}$ restricts to a two-sheeted covering map $q: S \to \mathbb{C} \setminus {0}$.

### Compactness and Proper Maps
- **Problem 11-10**: A covering map is proper if and only if it is a finite-sheeted covering.
- **Problem 11-11**: The total space $E$ of a covering is compact if and only if the base space $X$ is compact and the covering is finite-sheeted.
- **Double Cover of the Klein Bottle**: A proof of the two-sheeted covering of the Klein bottle by the 2-torus, utilizing coset decompositions and quotient topologies.
- **k-sheeted covered of connected sum**: A proof of the k-sheeted covering of the connected sum $M # N$ by a manifold of the form 
$\widetilde{M} # N # cdots # N$, utilizing the ball to be cut out of $M$ to lie inside an evenly covered neighborhood.

## Compilation Details

- **Compiler**: XeLaTeX / PDFLaTeX
- **Packages Used**: `amsmath`, `amssymb`, `amsthm`, `geometry`, `enumerate`

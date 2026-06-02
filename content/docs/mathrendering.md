---
draft: false
title: Math Rendering
weight: 70
---

This page is a rendering stress test for mathematical notation in the documentation theme. The content is intentionally fictional and exists only to verify display quality.

{{< callout type="info" >}}
All equations are synthetic examples. They are not research claims or validated methodology formulas.
{{< /callout >}}

## Inline Notation

Lorem ipsum notation can appear inline, such as \( \alpha_t \), \( \nabla_\theta \mathcal{L} \), \( \mathbb{E}[X] \), and \( O(n \log n) \), without breaking the reading flow.

## Bayesian Placeholder Model

{{< math >}}
p(\theta \mid \mathcal{D}) =
\frac{p(\mathcal{D} \mid \theta)\,p(\theta)}
{\int_{\Theta} p(\mathcal{D} \mid \vartheta)\,p(\vartheta)\,d\vartheta}
{{< /math >}}

## Matrix Objective

{{< math >}}
\mathbf{W}^{\star} =
\arg\min_{\mathbf{W} \in \mathbb{R}^{d \times k}}
\left[
\frac{1}{2n}\left\lVert \mathbf{X}\mathbf{W} - \mathbf{Y} \right\rVert_F^2
+ \lambda \operatorname{tr}\left(\mathbf{W}^{\top}\mathbf{L}\mathbf{W}\right)
\right]
{{< /math >}}

## Sequence Attention

{{< math >}}
\operatorname{Attention}(\mathbf{Q}, \mathbf{K}, \mathbf{V}) =
\operatorname{softmax}\left(
\frac{\mathbf{Q}\mathbf{K}^{\top}}{\sqrt{d_k}}
+ \mathbf{M}
\right)\mathbf{V}
{{< /math >}}

## Piecewise Demo Function

{{< math >}}
f(x) =
\begin{cases}
\sigma(\beta x) + \epsilon, & x \ge 0 \\
\log(1 + x^2) - \epsilon, & -1 < x < 0 \\
0, & x \le -1
\end{cases}
{{< /math >}}

## Constrained Optimization

{{< math >}}
\begin{aligned}
\underset{\mathbf{z},\,\mathbf{u}}{\text{maximize}}\quad
& \sum_{i=1}^{m} \omega_i \log(1 + z_i) - \rho \lVert \mathbf{u} \rVert_2^2 \\
\text{subject to}\quad
& \mathbf{A}\mathbf{z} + \mathbf{B}\mathbf{u} \preceq \mathbf{c}, \\
& z_i \ge 0,\quad i = 1,\ldots,m, \\
& \sum_{j=1}^{r} u_j = 1.
\end{aligned}
{{< /math >}}

## Integral Transform

{{< math >}}
\mathcal{T}\{g\}(\omega, \tau) =
\int_{-\infty}^{\infty}
g(t)\,
\exp\left(-\frac{(t-\tau)^2}{2s^2}\right)
e^{-i\omega t}\,dt
{{< /math >}}

## Probability Chain

{{< math >}}
\begin{aligned}
p(y_{1:T}, h_{1:T} \mid x_{1:T})
&= \prod_{t=1}^{T} p(y_t \mid h_t)\,p(h_t \mid h_{t-1}, x_t) \\
&= \prod_{t=1}^{T}
\operatorname{Cat}(y_t; \pi_t)\,
\mathcal{N}(h_t; \mu_t, \Sigma_t).
\end{aligned}
{{< /math >}}

## Symbol Table

| Symbol | Placeholder Meaning |
|---|---|
| \( \theta \) | Simulated parameter vector |
| \( \mathcal{D} \) | Placeholder dataset |
| \( \lambda \) | Demo regularization weight |
| \( \mathbf{L} \) | Synthetic graph Laplacian |
| \( \epsilon \) | Illustrative perturbation |

## Nested Summation

{{< math >}}
\mathcal{R}_{demo} =
\sum_{\ell=1}^{L}
\gamma_{\ell}
\left(
\sum_{i=1}^{n}
\sum_{j=1}^{n}
a_{ij}^{(\ell)}
\left\lVert
\phi_{\ell}(x_i) - \phi_{\ell}(x_j)
\right\rVert_2^2
\right)
{{< /math >}}

## Determinant And Trace

{{< math >}}
\log p(\mathbf{x}) =
-\frac{1}{2}
\left[
(\mathbf{x}-\boldsymbol{\mu})^{\top}\boldsymbol{\Sigma}^{-1}(\mathbf{x}-\boldsymbol{\mu})
+ \log \det(2\pi\boldsymbol{\Sigma})
\right]
{{< /math >}}

{{% details title="Rendering checklist" closed="true" %}}
- [x] Inline math
- [x] Fractions and integrals
- [x] Matrices and transposes
- [x] Piecewise functions
- [x] Aligned equations
- [x] Greek letters and calligraphic symbols
{{% /details %}}

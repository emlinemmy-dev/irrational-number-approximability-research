# Approximating Irrational Numbers and Points – Muhlenberg College Research

Undergraduate computational research conducted in collaboration with Professor Byungchul Cha and research partner Nolan Eichorn at Muhlenberg College. The project expanded higher-dimensional irrational approximations to quantify how closely quadratic irrational values and 2D points approximate rational counterparts.

## Abstract
This research focuses on examining how closely we can approximate any quadratic irrational number, $\alpha$, whose characteristic equation is $A\alpha^2 + B\alpha + C = 0$, where $A, B, C \in \mathbb{Z}$. The number $\alpha$ can be approximated by the convergents $\frac{p_n}{q_n}$ from the continued fraction expansion of $\alpha$. If $\alpha$ is purely periodic, we show that $A\frac{p_n^2}{q_n^2} + B\frac{p_n}{q_n} + C = \frac{c}{q_n^2}$. We also examine how closely we can approximate any quadratic irrational point $(\alpha, \beta)$ on the unit circle. We define the characteristic equation of the point by $p\alpha + q\beta - r = 0$, where $p, q, r \in \mathbb{Z}$. The point $(\alpha, \beta)$ can be approximated by $(\frac{a_n}{c_n}, \frac{b_n}{c_n})$, where $(a_n, b_n, c_n)$ are obtained from the Berggren tree. When $(\alpha, \beta)$ is purely periodic, we show that $|pa_n + qb_n - rc_n| = q - 1$.

## Computational & Analytical Highlights
* **Approximability Quantification:** Analyzed 1D and 2D convergence rates to determine the bounds of rational approximability for quadratic irrational numbers and unit circle points $(\alpha, \beta)$.
* **Algorithmic Automation:** Built Python automation scripts to compute continued fraction expansions and iterate Berggren trees, generating structured data points to evaluate error-bound behaviors.
* **Model Verification:** Derived and verified algebraic error-bound equations alongside faculty to maintain structural consistency across iterations.
* **Poster Presentation:** Co-presented research findings and computational models via a peer-reviewed research poster at the Joint Mathematics Meetings (JMM) in Seattle, WA.

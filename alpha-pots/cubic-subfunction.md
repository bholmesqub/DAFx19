---
layout: default
title: "Explicit solution for the cubic sub-function"
---

# Explicit solution for cubic subfunction coefficients

To fit a cubic function to the values and derivatives at the local limits \\(x_\mathrm{ll}\\) and \\(x_\mathrm{lh}\\), the following equations must be solved for:

<div>
\begin{align}
\bar{f}_\mathrm{cub}(x_\mathrm{ll}) &= y_\mathrm{ll} = c_4 x_\mathrm{ll}^3 + c_3 x_\mathrm{ll}^2 + c_2 x_\mathrm{ll} + c_1, \\
\bar{f}_\mathrm{cub}(x_\mathrm{lh}) &= y_\mathrm{lh} = c_4 x_\mathrm{lh}^3 + c_3 x_\mathrm{lh}^2 + c_2 x_\mathrm{lh} + c_1, \\
\bar{f}_\mathrm{cub}'(x_\mathrm{ll}) &= y_\mathrm{ll}' = 3 c_4 x_\mathrm{ll}^2 + 2 c_3 x_\mathrm{ll} + c_2, \\
\bar{f}_\mathrm{cub}'(x_\mathrm{lh}) &= y_\mathrm{lh}' = 3 c_4 x_\mathrm{lh}^2 + 2 c_3 x_\mathrm{lh} + c_2.
\end{align}
</div>

Though an explicit solution does exist it is complex and unintuitive to read. The result is displayed below for those who require it,

<div>
\begin{align}
  &\begin{split}
    c_1 &= -(2 y_\mathrm{ll} - 2 y_\mathrm{lh} - y_\mathrm{ll}' x_\mathrm{ll} + y_\mathrm{ll}' x_\mathrm{lh} - y_\mathrm{lh}' x_\mathrm{ll} + y_\mathrm{lh}' x_\mathrm{lh})/(x_\mathrm{ll} - x_\mathrm{lh})^3,\\[0.5em]
  \end{split}\\[1em]
  &\begin{split}
    c_2 &= (3 x_\mathrm{ll} y_\mathrm{ll} - 3 x_\mathrm{ll} y_\mathrm{lh} + 3 x_\mathrm{lh} y_\mathrm{ll} - 3 x_\mathrm{lh} y_\mathrm{lh} - y_\mathrm{ll}' x_\mathrm{ll}^2 + 2 y_\mathrm{ll}' x_\mathrm{lh}^2 \\[0.5em]
        & - 2 y_\mathrm{lh}' x_\mathrm{ll}^2 + y_\mathrm{lh}' x_\mathrm{lh}^2 - y_\mathrm{ll}' x_\mathrm{ll} x_\mathrm{lh} + y_\mathrm{lh}' x_\mathrm{ll} x_\mathrm{lh})/(x_\mathrm{ll} - x_\mathrm{lh})^3,
  \end{split} \\[1em]
  &\begin{split}
    c_3 &= -(y_\mathrm{ll}' x_\mathrm{lh}^3 - y_\mathrm{lh}' x_\mathrm{ll}^3 + y_\mathrm{ll}' x_\mathrm{ll} x_\mathrm{lh}^2 - 2 y_\mathrm{ll}' x_\mathrm{ll}^2 x_\mathrm{lh} + 2 y_\mathrm{lh}' x_\mathrm{ll} x_\mathrm{lh}^2 \\[0.5em]
    & - y_\mathrm{lh}' x_\mathrm{ll}^2 x_\mathrm{lh} + 6 x_\mathrm{ll} x_\mathrm{lh} y_\mathrm{ll} - 6 x_\mathrm{ll} x_\mathrm{lh} y_\mathrm{lh})/(x_\mathrm{ll} - x_\mathrm{lh})^3,
  \end{split}\\[1em]
  &\begin{split}
    c_4 &= (x_\mathrm{ll}^3 y_\mathrm{lh} - x_\mathrm{lh}^3 y_\mathrm{ll} + y_\mathrm{ll}' x_\mathrm{ll} x_\mathrm{lh}^3 - y_\mathrm{lh}' x_\mathrm{ll}^3 x_\mathrm{lh} + 3 x_\mathrm{ll} x_\mathrm{lh}^2 y_\mathrm{ll} \\[0.5em]
    &  - 3 x_\mathrm{ll}^2 x_\mathrm{lh} y_\mathrm{lh} - y_\mathrm{ll}' x_\mathrm{ll}^2 x_\mathrm{lh}^2 + y_\mathrm{lh}' x_\mathrm{ll}^2 x_\mathrm{lh}^2)/(x_\mathrm{ll} - x_\mathrm{lh})^3
  \end{split}
\end{align}
</div>

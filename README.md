# Teaching Portfolio

Amir Mohammad Mohammad Hosseini

I design and teach organic chemistry, biochemistry and physical chemistry for Iranian Chemistry Olympiad training. I mentored Iran’s teams at the International Chemistry Olympiad in 2025 and 2026. I also develop teaching materials on systems biology and AI in the life sciences.

## Sample lesson: Molecular conformations and the Boltzmann distribution

A molecule can adopt several conformations. If we know their energies, what can we say about how often each one occurs? This worked example is for students familiar with basic thermodynamics.

In a simplified model with discrete states at thermal equilibrium, the probability of state $i$ is its Boltzmann weight divided by the sum of all weights:

$$
w_i=\exp\left(-\frac{E_i}{RT}\right), \qquad p_i=\frac{w_i}{\sum_j w_j}.
$$

Here $E_i$ is a molar energy, $T$ is the temperature in kelvin, and $R=8.314\,\mathrm{J\,mol^{-1}\,K^{-1}}$. We can choose the energy zero freely: adding the same constant to every energy multiplies all weights by the same factor, which cancels in the probability.

### Worked example

Suppose there is one conformation of type A at energy zero, and two distinct conformations of type B, each $2.0\,\mathrm{kJ\,mol^{-1}}$ above A. At $298\,\mathrm{K}$, $RT\approx2.48\,\mathrm{kJ\,mol^{-1}}$. A has weight $1$ and each B conformation has weight $\exp(-2.0/2.48)\approx0.446$. Since both B conformations count as type B, we add their weights:

$$
P(B)=\frac{2(0.446)}{1+2(0.446)}\approx0.47.
$$

Each B conformation is less likely than A, but together they account for about 47% of the population. How many states a group contains matters as well as their energies.

### Exercise

Keep the same temperature and energy gap. How many distinct B conformations would make type B more probable than A?

<details>
<summary>Solution</summary>

With $n$ B conformations, their combined weight is $n(0.446)$. The smallest integer for which that weight exceeds $1$ is $3$, giving $P(B)\approx0.57$.

</details>

For a real molecule, each conformational basin covers a range of geometries. Its population depends on the weights across the whole basin, not just the energy at its minimum.

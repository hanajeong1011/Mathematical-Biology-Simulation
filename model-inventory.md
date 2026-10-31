# Model inventory

This inventory follows the uploaded lecture notes (Weeks 1–7). The page number is the page in the original weekly PDF file. The catalogue excludes exponential growth and decay, mass-action kinetics, and the phosphorylation–dephosphorylation cycle, as requested. The additional diffusion predator–prey model discussed for a later update is not included.

| Menu section | Model | Main state variables | Interactive view | First introduced |
|---|---|---|---|---|
| Types of bifurcation | Saddle-node normal form | State `x`, parameter `r` | State/derivative plot and equilibrium branches | Week 1, p. 5 |
| Types of bifurcation | Transcritical normal form | State `x`, parameter `r` | State/derivative plot and equilibrium branches | Week 1, p. 6 |
| Types of bifurcation | Supercritical pitchfork normal form | State `x`, parameter `r` | Paired normal forms and equilibrium branches | Week 1, p. 6 |
| Types of bifurcation | Subcritical pitchfork normal form | State `x`, parameter `r` | Paired normal forms and equilibrium branches | Week 1, p. 7 |
| 1. One-dimensional systems | Logistic population growth | Population `x` | State/derivative plot | Week 1, p. 8 |
| 1. One-dimensional systems | Single-population SIS epidemic | Infected population `I` | Reduced state/derivative plot | Week 2, p. 1 |
| 1. One-dimensional systems | Logistic growth with harvesting | Population `x` | State/derivative plot and equilibria | Week 2, p. 2 |
| 1. One-dimensional systems | Spruce budworm outbreak | Budworm population `N` | State/derivative plot and refuge/outbreak equilibria | Week 2, p. 3 |
| 1. One-dimensional systems | Michaelis–Menten enzyme kinetics | Substrate `s`, complex `c` | Substrate–complex projection | Week 2, p. 12 |
| 2. Multidimensional systems | Two interacting SIS populations | Infective fractions `u`, `v` | Phase portrait | Week 3, p. 8 |
| 2. Multidimensional systems | Lotka–Volterra predator–prey | Prey `N`, predator `P` | Phase portrait | Week 3, p. 13 |
| 2. Multidimensional systems | Autoregulatory genetic switch | Protein `u`, mRNA `v` | Phase portrait | Week 4, p. 1 |
| 2. Multidimensional systems | Wilson–Cowan neural populations | Firing rates `u₁`, `u₂` | Phase portrait | Week 4, p. 8 |
| 2. Multidimensional systems | Two-species competition | Populations `N₁`, `N₂` | Phase portrait | Week 4, p. 10 |
| 2. Multidimensional systems | Continuous-time Hopfield network | Unit activities | Phase portrait and energy descent | Week 4, p. 15 |
| 3. Oscillations and bifurcations | Two-component negative-feedback loop | `x`, `y` | Phase portrait | Week 5, p. 3 |
| 3. Oscillations and bifurcations | Logistic/saturating predator–prey | Prey `N`, predator `P` | Phase portrait | Week 5, p. 4 |
| 3. Oscillations and bifurcations | Repressilator | Repressor concentrations | Projection of 3D trajectory | Week 5, p. 16 |
| 3. Oscillations and bifurcations | Hopf normal form | `x`, `y` | Phase portrait and limit cycle | Week 5, p. 20 |
| 3. Oscillations and bifurcations | FitzHugh–Nagumo neuron | Voltage `v`, recovery `w` | Phase portrait | Week 6, p. 5 |
| 3. Oscillations and bifurcations | Hodgkin–Huxley neuron | Voltage and channel gates | Projection of 4D trajectory | Week 6, p. 4 |
| 3. Oscillations and bifurcations | Phase oscillator / synchronisation | Phase difference `ψ` | State/derivative plot | Week 6, p. 14 |
| 4. Spatial dynamics | Fisher–Kolmogorov equation | Density `u(x,t)` | `U–V` travelling-wave portrait, spatial profile | Week 7, p. 3 |
| 4. Spatial dynamics | Spatial SIS epidemic | Susceptible and infected densities | Travelling-wave portrait, spatial profile | Week 7, p. 9 |
| 4. Spatial dynamics | Rabies spread in foxes | Susceptible and infected densities | Local reaction portrait, spatial pulse profile | Week 7, p. 10 |
| 4. Spatial dynamics | Diffusive predator–prey model (lecture-only) | Prey `u`, predator `v`, predator gradient `W` | 3D travelling-wave phase portrait with mouse rotation | Not in the notes PDF |

## Interpretation notes

- The one-population SIS model remains available as the simpler comparison for the two-population interacting SIS model.
- Saddle-node, transcritical, and pitchfork normal forms are grouped separately in the menu for easier study. The two pitchfork forms share a page and each has its own stable/unstable equilibrium-branch diagram.
- The Michaelis–Menten, repressilator, and Hodgkin–Huxley plots show lower-dimensional projections of higher-dimensional models.
- The spatial SIS phase view is a scalar travelling-wave reduction using infected density and its spatial gradient. The rabies phase view shows local reaction dynamics with diffusion omitted; its spatial profile includes diffusion.
- Spatial PDE profiles are qualitative explicit finite-difference simulations on a one-dimensional grid with no-flux boundaries.
- The lecture-only predator–prey model uses `ξ = x − cτ` and `W = dV/dξ`; the phase-space trajectory is integrated in `ξ`. Its initial profile selects the wave orientation, while the sign of `c` determines rightward or leftward translation for the chosen travelling-wave convention.

# Model inventory from the lecture notes

This inventory is based on the uploaded **Lecture Notes — Weeks 1–7**. Chapter labels follow the chapter/topic headings in those notes. Equations in the site use simplified notation where the original notes nondimensionalise a model or introduce a reduction.

| Chapter | Model | Main state variables | Simulation view |
|---|---|---|---|
| 1. One-dimensional systems | Exponential growth / decay | Population size `x` | State versus derivative graph |
| 1. One-dimensional systems | Logistic population growth | Population size `x` | State versus derivative graph |
| 1. One-dimensional systems | Saddle-node normal form | State `x`, parameter `μ` | State versus derivative graph |
| 1. One-dimensional systems | Transcritical normal form | State `x`, parameter `μ` | State versus derivative graph |
| 1. One-dimensional systems | Supercritical pitchfork normal form | State `x`, parameter `μ` | State versus derivative graph |
| 1. One-dimensional systems | Subcritical pitchfork normal form | State `x`, parameter `μ` | State versus derivative graph |
| 1. One-dimensional systems | SIS epidemic model | Infected population `I`, with fixed total `N` | Reduced state versus derivative graph |
| 1. One-dimensional systems | Logistic growth with harvesting | Population size `x` | State versus derivative graph and equilibria |
| 1. One-dimensional systems | Spruce budworm outbreak | Budworm population `N` | State versus derivative graph and refuge/outbreak equilibria |
| 1. One-dimensional systems | Mass-action reaction kinetics | Reactants `A`, `B`; product `C` | `A`–`B` phase-plane projection for an elementary reaction |
| 1. One-dimensional systems | Michaelis–Menten enzyme kinetics | Substrate `s`, complex `c`, product `p` | Substrate–complex phase-plane projection |
| 1. One-dimensional systems | Phosphorylation–dephosphorylation cycle | Modified protein `W*` | Reduced state versus derivative graph |
| 2. Multidimensional systems | Two interacting SIS populations | Infective fractions `u`, `v` | Phase portrait |
| 2. Multidimensional systems | Lotka–Volterra predator–prey | Prey `N`, predator `P` | Phase portrait |
| 2. Multidimensional systems | Autoregulatory genetic switch | Protein and mRNA concentrations `u`, `v` | Phase portrait |
| 2. Multidimensional systems | Wilson–Cowan neural populations | Mean firing rates `u₁`, `u₂` | Phase portrait |
| 2. Multidimensional systems | Two-species competition | Populations `N₁`, `N₂` | Phase portrait |
| 2. Multidimensional systems | Continuous-time Hopfield network | Two example units | Phase portrait / energy descent illustration |
| 3. Oscillations and bifurcations | Two-component negative-feedback loop | `x`, `y` | Phase portrait; representative feedback functions |
| 3. Oscillations and bifurcations | Logistic/saturating predator–prey model | Prey `N`, predator `P` | Phase portrait |
| 3. Oscillations and bifurcations | Repressilator | Three repressor concentrations | `x₁`–`x₂` projection of a 3D trajectory |
| 3. Oscillations and bifurcations | Hopf normal form | Complex amplitude `A` | Phase portrait and limit cycle |
| 3. Oscillations and bifurcations | FitzHugh–Nagumo neuron | Voltage `v`, recovery `w` | Phase portrait |
| 3. Oscillations and bifurcations | Hodgkin–Huxley neuron | Voltage and channel gates `V,m,h,n` | `V`–`m` projection of a 4D trajectory |
| 3. Oscillations and bifurcations | Phase oscillator / synchronisation | Phase difference `ψ` | State versus derivative graph |
| 4. Spatial dynamics | Fisher–Kolmogorov equation | Population / gene density `u(x,t)` | 1D reaction–diffusion profile |
| 4. Spatial dynamics | Spatial SIS epidemic | Susceptible and infected densities | 1D reaction–diffusion profile |
| 4. Spatial dynamics | Rabies spread in foxes | Susceptible and infected densities | 1D travelling-pulse illustration |

## Scope notes

- The genetic-switch card follows the notes’ positive autoregulation model: protein stimulates mRNA production, and mRNA produces protein.
- The notes introduce the saddle-node, transcritical, and supercritical/subcritical pitchfork normal forms as general dynamical-systems examples. They are included alongside the biological models because they are explicit model equations in the course.
- The mass-action section derives a general reaction-network framework and includes elementary reaction examples. The interactive card uses the `A + 2B → C` example; Michaelis–Menten and the phosphorylation cycle are included as biologically named kinetic models.
- A plot of a 3D or 4D model is a projection, not a complete phase portrait. The site labels those projections explicitly.
- Spatial PDE plots use an explicit finite-difference method on a one-dimensional grid with no-flux boundaries and representative parameters; they are qualitative teaching simulations, not calibrated or precision PDE solvers.

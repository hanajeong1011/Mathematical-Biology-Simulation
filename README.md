# Mathematical Biology Simulation

A small, dependency-free interactive companion to the Mathematical Biology lecture notes (Weeks 1–7).

Open `index.html` in a modern browser. The file is self-contained, including native MathML equations, and works offline. Expand a chapter, select a model, adjust its named parameters and initial conditions, then press Play. Sliders and numeric inputs use one decimal place.

One-dimensional models plot the state against its derivative, `f(x)`. Two-dimensional models show trajectories and directional arrows. Small labelled markers distinguish fixed points (F.P.), initial conditions (I.C.), and the moving state. An on-plot legend explains stability colours; analytic equilibrium expressions appear below the graph when available. Both pitchfork normal forms share one comparison page.

Each model identifies the first introduction in the uploaded weekly PDF, using that PDF's own page number. The page references do not refer to a combined semester PDF. Palette alternatives have been proposed separately; the existing green theme remains until one is selected.

## Models represented

- **Chapter 1 — One-dimensional systems:** exponential growth, logistic growth, the saddle-node, transcritical and pitchfork normal forms, single-population SIS, logistic growth with harvesting, spruce budworm outbreak, mass-action kinetics, Michaelis–Menten enzyme kinetics, and a reduced phosphorylation–dephosphorylation cycle.
- **Chapter 2 — Multidimensional systems:** two-population SIS, Lotka–Volterra predator–prey, genetic switch, Wilson–Cowan populations, two-species competition, and a two-unit continuous-time Hopfield example.
- **Chapter 3 — Oscillations and bifurcations:** delayed negative feedback, logistic/saturating predator–prey, repressilator, Hopf normal form, FitzHugh–Nagumo, Hodgkin–Huxley, and phase oscillator/synchronisation.
- **Chapter 4 — Spatial dynamics:** Fisher–Kolmogorov, spatial SIS, and rabies spread in foxes.

The catalogue and qualifications for higher-dimensional projections are listed in [`model-inventory.md`](model-inventory.md). The simulations are teaching illustrations with dimensionless or representative parameter choices; they are not calibrated predictions for a particular biological system.

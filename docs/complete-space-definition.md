# Complete Space Definition for Temporal Vector Theory

## Status

This document defines the current **provisional answer** to the first foundational question of Temporal Vector Theory (TVT):

> What is the complete space in which the theory is defined?

The construction below is a candidate research model, not an established physical fact.

## 1. Total dimensionality

TVT assumes a smooth twelve-dimensional manifold

```math
\mathcal M_{12}
```

with nine spacelike directions and three timelike directions. Using the convention that timelike directions carry positive sign, the metric signature is provisionally

```math
(3,9).
```

A local coordinate chart is written as

```math
Z^A = \left(
 x_\tau^1,x_\tau^2,x_\tau^3,
 x_\sigma^1,x_\sigma^2,x_\sigma^3,
 x_\rho^1,x_\rho^2,x_\rho^3,
 \tau,\sigma,\rho
\right).
```

The manifold is therefore locally organized into three sectors:

```math
\mathcal S_\tau^{3,1},\qquad
\mathcal S_\sigma^{3,1},\qquad
\mathcal S_\rho^{3,1}.
```

Locally,

```math
\mathcal M_{12}
\simeq
\mathcal S_\tau^{3,1}
\times
\mathcal S_\sigma^{3,1}
\times
\mathcal S_\rho^{3,1}.
```

This local product notation does not require the three sectors to be globally independent.

## 2. Base-and-fiber interpretation

The preferred geometric interpretation is a fibered space rather than three disconnected spacetimes.

The observable sector is used as a four-dimensional base:

```math
\mathcal B_4 \equiv \mathcal S_\tau^{3,1}.
```

The two hidden sectors form an eight-dimensional fiber:

```math
\mathcal F_8
\equiv
\mathcal S_\sigma^{3,1}
\times
\mathcal S_\rho^{3,1}.
```

The total space is written as a fiber bundle

```math
\mathcal F_8
\hookrightarrow
\mathcal M_{12}
\xrightarrow{\ \pi\ }
\mathcal B_4.
```

At each event in the observable spacetime, the theory associates an internal hidden spacetime structure containing two additional temporal and six additional spatial coordinates.

This allows the hidden sectors to vary, twist, or couple across the observable base instead of behaving as rigid parallel universes.

## 3. Spatial sector structure

Define three spatial triplets:

```math
\mathbf X_\tau=(x_\tau^1,x_\tau^2,x_\tau^3),
```

```math
\mathbf X_\sigma=(x_\sigma^1,x_\sigma^2,x_\sigma^3),
```

```math
\mathbf X_\rho=(x_\rho^1,x_\rho^2,x_\rho^3).
```

The full spatial structure is therefore

```math
\mathbf X_9
=
(\mathbf X_\tau,\mathbf X_\sigma,\mathbf X_\rho).
```

The six hidden spatial dimensions may be compact or effectively confined. The simplest provisional topology for later calculations is

```math
\mathcal K_6
=
\mathbb T_\sigma^3
\times
\mathbb T_\rho^3,
```

where each hidden spatial triplet is modeled as a three-torus. This is a calculational placeholder, not a final claim about compactification geometry.

The hidden temporal coordinates are provisionally non-compact:

```math
\sigma,\rho\in\mathbb R.
```

Compact timelike directions are avoided at this stage because they would naturally introduce closed timelike curves.

## 4. Temporal sector structure

The temporal coordinate vector is

```math
\mathbf T=(\tau,\sigma,\rho).
```

A physical system carries a temporal orientation vector

```math
\mathbf u_T=(u_\tau,u_\sigma,u_\rho).
```

The current kinematic ansatz is

```math
u_\tau^2+u_\sigma^2+u_\rho^2=1.
```

The observable proper-time direction is the projection selected by the observer's temporal orientation.

For ordinary low-velocity matter,

```math
\mathbf u_T\approx(1,0,0).
```

This aligns observation predominantly with the `tau` sector.

## 5. Observable spacetime as a section

The observable universe is not identified with the entire twelve-dimensional manifold. It is represented by a four-dimensional section or leaf

```math
s:\mathcal B_4\rightarrow\mathcal M_{12}.
```

An observer samples the total geometry only along this section.

The effective observed spatial coordinate is provisionally written as

```math
\mathbf x_{\mathrm{obs}}
=
u_\tau\mathbf X_\tau
+
u_\sigma\mathbf X_\sigma
+
u_\rho\mathbf X_\rho.
```

More generally, inter-sector mixing is described by a coupling matrix

```math
\mathbf x_{\mathrm{obs}}^a
=
P^a{}_{Ai}(\mathbf u_T,Z)\,X^{Ai},
```

where `P` is a projection map determined by temporal orientation and geometry.

## 6. Zeroth-order geometry

At the uncoupled level, the total line element is provisionally

```math
\begin{aligned}
dS^2 ={}& c^2d\tau^2-d\mathbf X_\tau^2 \\
&+c^2d\sigma^2-d\mathbf X_\sigma^2 \\
&+c^2d\rho^2-d\mathbf X_\rho^2.
\end{aligned}
```

Equivalently,

```math
dS^2
=
c^2(d\tau^2+d\sigma^2+d\rho^2)
-
\sum_{A\in\{\tau,\sigma,\rho\}}d\mathbf X_A^2.
```

This block-diagonal metric is only the zeroth-order candidate. A general TVT metric may contain cross-sector terms:

```math
dS^2=G_{AB}(Z)dZ^A dZ^B.
```

The off-diagonal components encode coupling among the three sectors.

## 7. Why this answers the first foundational question

The complete space of TVT is provisionally defined by all of the following, not merely by the number twelve:

1. a smooth connected twelve-dimensional manifold `M_12`;
2. nine spacelike and three timelike directions;
3. a local decomposition into three `3+1` sectors;
4. a four-dimensional observable base and an eight-dimensional hidden fiber;
5. six hidden spatial dimensions that may be compactified or confined;
6. two additional non-compact temporal dimensions;
7. a temporal orientation vector selecting the observer's effective section;
8. a projection map from the full geometry to observed `3+1` spacetime;
9. a general pseudo-Riemannian metric capable of coupling the sectors.

## 8. Relation to existing higher-dimensional approaches

The dimensional count overlaps with some twelve-dimensional constructions, but the interpretation is different.

- In F-theory, twelve-dimensional geometry often functions as an auxiliary geometric encoding rather than a directly traversable `9+3` spacetime.
- In two-time physics, additional gauge constraints are introduced to remove unphysical degrees of freedom and recover ordinary one-time systems.
- In compactified string models, hidden spatial dimensions are typically internal geometries associated with one physical time.

TVT instead proposes a specific correspondence:

```math
3\text{ temporal directions}
\longleftrightarrow
3\text{ spatial triplets}.
```

This correspondence is the distinctive structural hypothesis of the current candidate space.

## 9. Remaining dependencies

The first foundational question is considered **provisionally closed**, but the candidate survives only if later work can provide:

- a stable metric and causal structure;
- a constraint or gauge mechanism that removes negative-norm modes;
- exact recovery of Lorentz symmetry in the observable sector;
- a physical compactification or confinement mechanism;
- a consistent dynamical law for temporal orientation;
- at least one falsifiable prediction.

Failure on any of these points may require replacing this candidate geometry.

## Provisional definition

> Temporal Vector Theory is defined on a smooth fibered pseudo-Riemannian manifold of dimension twelve and signature `(3,9)`, locally decomposed into three coupled `3+1` sectors. Observable spacetime is a four-dimensional section selected by temporal orientation, while two hidden temporal directions and six hidden spatial directions form an internal eight-dimensional fiber.

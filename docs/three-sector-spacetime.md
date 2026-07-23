# Three-Sector Spacetime Hypothesis

## Status

This document records a **candidate architecture** for Temporal Vector Theory (TVT). It is not yet a derived result and must be tested for mathematical consistency, stability, covariance, and compatibility with established physics.

## Core proposal

TVT may be formulated on a twelve-dimensional manifold with nine spatial and three temporal dimensions:

```math
\mathcal U^{9,3}.
```

The full geometry is organized as three coupled `3+1` sectors:

```math
\mathcal U^{9,3}
=
\mathcal S_\tau^{3,1}
\oplus
\mathcal S_\sigma^{3,1}
\oplus
\mathcal S_\rho^{3,1}.
```

Each sector contains one temporal direction and one associated three-dimensional spatial subspace:

```math
\mathcal S_\tau^{3,1}=(\mathbf X_\tau,\tau),
\qquad
\mathcal S_\sigma^{3,1}=(\mathbf X_\sigma,\sigma),
\qquad
\mathcal S_\rho^{3,1}=(\mathbf X_\rho,\rho),
```

with

```math
\mathbf X_\tau=(x_1,x_2,x_3),
```

```math
\mathbf X_\sigma=(x_4,x_5,x_6),
```

```math
\mathbf X_\rho=(x_7,x_8,x_9).
```

## Candidate interval

A first flat-space candidate is

```math
dS^2
=
c^2(d\tau^2+d\sigma^2+d\rho^2)
-
\sum_{i=1}^{9}dx_i^2.
```

Equivalently,

```math
\begin{aligned}
dS^2={}&
\left(c^2d\tau^2-d\mathbf X_\tau^2\right)
+
\left(c^2d\sigma^2-d\mathbf X_\sigma^2\right)
+
\left(c^2d\rho^2-d\mathbf X_\rho^2\right).
\end{aligned}
```

This corresponds to a candidate metric signature `(3,9)` under the convention that temporal directions carry positive sign.

The final theory is not required to preserve this diagonal block form. Cross-sector terms may be necessary:

```math
dS^2=G_{AB}\,dX^A dX^B,
```

where `G_{AB}` may contain couplings between temporal and spatial sectors.

## Temporal orientation

The local temporal state is represented by a normalized orientation vector

```math
\mathbf u_T=(u_\tau,u_\sigma,u_\rho),
```

with

```math
u_\tau^2+u_\sigma^2+u_\rho^2=1.
```

The current kinematic parametrization is

```math
u_\tau=\sqrt{1-\frac{v^2}{c^2}},
\qquad
u_\sigma=\frac vc\cos\varphi,
\qquad
u_\rho=\frac vc\sin\varphi.
```

## Observed-space projection

A central hypothesis is that an observer does not access all nine spatial directions directly. Instead, the experienced three-dimensional space is a projection selected by the observer's temporal orientation.

Define the spatial-sector matrix

```math
\mathbb X=
\begin{pmatrix}
\mathbf X_\tau\\
\mathbf X_\sigma\\
\mathbf X_\rho
\end{pmatrix}.
```

The observed spatial vector is then proposed to be

```math
\boxed{
\mathbf x_{\mathrm{obs}}
=
u_\tau\mathbf X_\tau
+u_\sigma\mathbf X_\sigma
+u_\rho\mathbf X_\rho
}
```

or compactly,

```math
\mathbf x_{\mathrm{obs}}=\mathbf u_T^{\mathsf T}\mathbb X.
```

For ordinary matter in the low-velocity regime,

```math
\mathbf u_T\approx(1,0,0),
```

so that

```math
\mathbf x_{\mathrm{obs}}\approx\mathbf X_\tau.
```

This provides a candidate explanation for why only three spatial dimensions are directly accessible even if the full geometry contains nine.

## Coupling between temporal and spatial sectors

A strict one-to-one rule,

```math
\tau\leftrightarrow\mathbf X_\tau,
\qquad
\sigma\leftrightarrow\mathbf X_\sigma,
\qquad
\rho\leftrightarrow\mathbf X_\rho,
```

is likely too restrictive because photons satisfy zero ordinary proper time while propagating through observed space.

A more general candidate is

```math
d\mathbf X_A=M_{AB}u_T^B\,d\lambda,
```

where `M_{AB}` is a coupling matrix between temporal orientation and spatial motion. The physical meaning, symmetry properties, and dynamics of `M_{AB}` remain undefined.

## Matter sectors

This architecture suggests, but does not yet derive, the following working interpretation:

- **ordinary matter:** orientation dominated by `\tau` and therefore projected mainly onto `\mathbf X_\tau`;
- **antimatter:** the same observable causal orientation with opposite hidden temporal orientation;
- **dark matter:** matter concentrated in the `\sigma` or `\rho` sectors whose gravitational influence projects into `\mathbf X_\tau` while electromagnetic coupling is suppressed;
- **dark energy:** a possible collective effect of curvature, vacuum structure, or tension across the coupled sectors.

These identifications are speculative and cannot be treated as physical explanations until a field theory and quantitative observables are derived.

## Relation to higher-dimensional models

The proposal is structurally compatible with the idea that additional spatial dimensions may be hidden or compactified, but it differs by assigning the nine spatial directions to three temporally related `3+1` sectors.

The distinctive TVT hypothesis is therefore

```math
\boxed{
3\text{ temporal directions}
\longleftrightarrow
3\text{ spatial three-dimensional sectors}
}
```

rather than merely adding two temporal dimensions to an otherwise unchanged spacetime.

## Required consistency tests

This candidate geometry must answer at least the following questions:

1. What symmetry group preserves the full interval?
2. How is ordinary Lorentz invariance recovered exactly?
3. Does the `(9,3)` signature introduce ghosts or negative-energy states?
4. What constraint or gauge symmetry removes unphysical temporal degrees of freedom?
5. How does causality emerge for observers confined to one projection?
6. Why do photons remain in observed space when ordinary proper time vanishes?
7. What determines the coupling matrix `M_{AB}`?
8. Can the model reproduce gravitational lensing and structure formation without contradiction?
9. Does the theory produce a testable prediction not already contained in relativity or existing higher-dimensional models?

## Working principle

The hypothesis can be summarized as follows:

> The full universe may consist of three coupled spacetime sectors, each containing one temporal and three spatial dimensions. The three-dimensional space experienced by an observer is the projection of the full nine-dimensional spatial geometry selected by that observer's temporal orientation.

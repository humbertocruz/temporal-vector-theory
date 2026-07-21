# Minimal Coupled Metric for Temporal Vector Theory

## Status

This document develops the first minimal metric candidate for Temporal Vector Theory (TVT). It is an exploratory ansatz, not an established physical law.

The construction follows three design rules:

1. each `3+1` sector must recover ordinary Minkowski geometry when isolated;
2. spatial axes remain orthonormal within each sector;
3. genuinely new physics is confined initially to couplings between temporal sectors.

## 1. Coordinates

Use the ordered coordinates

```math
Z^A=(\tau,\sigma,\rho,\mathbf X_\tau,\mathbf X_\sigma,\mathbf X_\rho),
```

where each spatial triplet is

```math
\mathbf X_A=(x_A,y_A,z_A),
\qquad A\in\{\tau,\sigma,\rho\}.
```

The sign convention is temporal-positive and spatial-negative.

## 2. Zeroth-order metric

With no coupling, the line element is

```math
 dS_0^2
 =c^2(d\tau^2+d\sigma^2+d\rho^2)
 -d\mathbf X_\tau^2
 -d\mathbf X_\sigma^2
 -d\mathbf X_\rho^2.
```

The corresponding metric is block diagonal:

```math
G_0=
\begin{pmatrix}
I_3 & 0\\
0 & -I_9
\end{pmatrix},
```

with signature `(3,9)`.

## 3. Minimal temporal coupling

The smallest symmetric coupling that treats the three temporal axes equivalently is

```math
K(\varepsilon)=
\begin{pmatrix}
1 & \varepsilon & \varepsilon\\
\varepsilon & 1 & \varepsilon\\
\varepsilon & \varepsilon & 1
\end{pmatrix}.
```

The complete minimal metric is

```math
G(\varepsilon)=
\begin{pmatrix}
K(\varepsilon) & 0\\
0 & -I_9
\end{pmatrix}.
```

Its line element is

```math
\begin{aligned}
dS^2={}&c^2\left(d\tau^2+d\sigma^2+d\rho^2\right)\\
&+2\varepsilon c^2\left(d\tau\,d\sigma+d\tau\,d\rho+d\sigma\,d\rho\right)\\
&-d\mathbf X_\tau^2-d\mathbf X_\sigma^2-d\mathbf X_\rho^2.
\end{aligned}
```

Thus ordinary sector geometry remains unchanged on the diagonal, while all novelty appears in cross-temporal terms.

## 4. Eigenmodes

The temporal matrix has one symmetric eigenvector

```math
\mathbf v_+=(1,1,1)/\sqrt3
```

with eigenvalue

```math
\lambda_+=1+2\varepsilon,
```

and two independent difference modes orthogonal to `v_+`, both with eigenvalue

```math
\lambda_-=1-\varepsilon.
```

The symmetric mode describes common evolution of all temporal sectors. The two difference modes describe relative temporal orientation among the sectors.

## 5. Signature-preserving bound

To keep all three temporal eigenvalues positive, require

```math
1+2\varepsilon>0,
\qquad
1-\varepsilon>0.
```

Therefore

```math
\boxed{-\frac12<\varepsilon<1}.
```

Within this interval, the full metric preserves signature `(3,9)`.

Special limits are:

```math
\varepsilon=0
```

for three uncoupled temporal axes;

```math
\varepsilon\rightarrow1
```

where the two relative modes become degenerate and lose norm;

```math
\varepsilon\rightarrow-\frac12
```

where the common temporal mode loses norm.

The boundary values are excluded because the metric becomes singular.

## 6. Inverse temporal metric

For later field equations, the inverse is

```math
K^{-1}
=
\frac{1}{1-\varepsilon}I_3
-
\frac{\varepsilon}{(1-\varepsilon)(1+2\varepsilon)}J_3,
```

where `J_3` is the matrix whose entries are all one.

Equivalently,

```math
K^{-1}_{AA}
=
\frac{1+\varepsilon}{(1-\varepsilon)(1+2\varepsilon)},
```

and, for `A\neq B`,

```math
K^{-1}_{AB}
=
-\frac{\varepsilon}{(1-\varepsilon)(1+2\varepsilon)}.
```

## 7. Determinant

The determinant of the temporal block is

```math
\det K=(1-\varepsilon)^2(1+2\varepsilon).
```

Hence the metric is non-degenerate precisely away from

```math
\varepsilon=1,
\qquad
\varepsilon=-\frac12.
```

## 8. Orientation-dependent coupling

A constant `epsilon` is only the background model. The TVT hypothesis suggests that coupling should depend on temporal orientation.

For sectors or systems `A` and `B`, define

```math
\chi_{AB}=\mathbf u_A\cdot\mathbf u_B.
```

A minimal dynamical extension is

```math
\varepsilon_{AB}(Z)
=\lambda\,F(\chi_{AB}(Z)),
```

where:

- `lambda` is an overall coupling scale;
- `F` is an alignment law;
- `chi_AB` measures relative temporal orientation.

The symmetric temporal metric becomes

```math
K_{AB}=\delta_{AB}+(1-\delta_{AB})\varepsilon_{AB}.
```

The constant symmetric model is recovered when all off-diagonal couplings are equal.

## 9. First physical interpretation

The diagonal entries state that each temporal direction has the same local normalization as ordinary time.

The off-diagonal entries state that evolution along one temporal direction contributes partly to interval measured along another temporal sector.

For positive `epsilon`, aligned temporal displacements increase the common-mode interval. For negative `epsilon`, common evolution is suppressed while relative modes are enhanced.

This sign distinction may eventually separate attractive, repulsive, clustering, or vacuum-like effective behavior, but no such identification is established yet.

## 10. What this model already decides

The minimal model provides:

1. a concrete twelve-dimensional metric;
2. exact recovery of uncoupled `3+1` sectors at `epsilon = 0`;
3. an explicit stability interval for the background temporal block;
4. common and relative temporal eigenmodes;
5. a path from constant coupling to orientation-dependent coupling.

## 11. What it does not yet solve

This ansatz does not yet prove:

- causal consistency with three physical times;
- absence of negative-norm quantum states;
- a gauge constraint that removes unphysical modes;
- a unique coupling function `F`;
- recovery of general relativity after dimensional reduction;
- a dark-matter or dark-energy equation of state;
- any distinct experimental prediction.

## Provisional metric principle

> Each TVT sector retains ordinary local `3+1` geometry. The first new geometric degree of freedom is a symmetric coupling among temporal directions. In the maximally symmetric background, this coupling is described by one parameter `epsilon`, whose signature-preserving range is `-1/2 < epsilon < 1`. More generally, the off-diagonal temporal metric components are functions of relative temporal orientation.

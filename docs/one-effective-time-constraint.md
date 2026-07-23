# One-Effective-Time Constraint and the First Stability Test

## Status

This document performs the first dynamical stability test of the minimal coupled temporal metric used in Temporal Vector Theory (TVT).

The result is provisional but important:

> A field that evolves independently along all three timelike coordinates has an energy functional that is unbounded below when one temporal coordinate is selected as the observer's evolution parameter.

The minimal resolution adopted here is that a physical excitation has three-dimensional **temporal orientation**, but only one effective temporal direction is dynamically traversed at a time.

This is a speculative construction, not an established physical theory.

## 1. Minimal temporal metric

The temporal metric is

```math
K(\varepsilon)=
\begin{pmatrix}
1&\varepsilon&\varepsilon\\
\varepsilon&1&\varepsilon\\
\varepsilon&\varepsilon&1
\end{pmatrix},
```

with positive-definiteness condition

```math
-\frac12<\varepsilon<1.
```

The full zeroth-order metric is

```math
G=
\begin{pmatrix}
K&0\\
0&-I_9
\end{pmatrix}.
```

## 2. Naive scalar field

Consider a real scalar field `phi` with Lagrangian density

```math
\mathcal L
=
\frac12 G^{MN}\partial_M\phi\,\partial_N\phi
-V(\phi).
```

For the uncoupled case `epsilon = 0`, the kinetic part is

```math
\mathcal L
=
\frac12(\partial_\tau\phi)^2
+\frac12(\partial_\sigma\phi)^2
+\frac12(\partial_\rho\phi)^2
-\frac12|\nabla_9\phi|^2
-V(\phi).
```

Choose `tau` as the evolution coordinate observed in the visible sector. The canonical momentum is

```math
\pi_\tau=\frac{\partial\mathcal L}{\partial(\partial_\tau\phi)}
=\partial_\tau\phi.
```

The Hamiltonian density becomes

```math
\mathcal H_\tau
=
\frac12\pi_\tau^2
-\frac12(\partial_\sigma\phi)^2
-\frac12(\partial_\rho\phi)^2
+\frac12|\nabla_9\phi|^2
+V(\phi).
```

The hidden-time gradient terms have negative sign in the `tau`-Hamiltonian. Arbitrarily rapid variation in `sigma` or `rho` can therefore drive

```math
\mathcal H_\tau\rightarrow-\infty.
```

Thus positivity of the twelve-dimensional metric eigenvalues is not enough to guarantee dynamical stability.

## 3. Physical interpretation of the failure

The failure occurs because the naive model treats all three temporal coordinates as independent evolution parameters for the same physical degree of freedom.

TVT does not require this interpretation.

The original temporal-vector hypothesis states that a physical system carries one normalized orientation

```math
\mathbf u_T=(u_\tau,u_\sigma,u_\rho),
```

not three unrelated clocks simultaneously advancing independently.

This motivates a distinction:

```math
\text{temporal dimension}
\neq
\text{independent dynamical clock}.
```

The three-dimensional temporal space specifies possible directions of evolution. A physical excitation follows one effective direction through that space.

## 4. Effective temporal coordinate

Let a physical system have temporal orientation `u_T`. Define the effective temporal differential

```math
ds_T
=
N_u\,u_A\,dT^A,
```

where

```math
T^A=(\tau,\sigma,\rho)
```

and `N_u` is a normalization determined by the temporal metric.

Using the inverse metric, define

```math
\kappa_u
=
u_A(K^{-1})^{AB}u_B.
```

For positive-definite `K`,

```math
\kappa_u>0
```

for every nonzero temporal orientation. A normalized effective derivative may be written as

```math
D_u
=
\frac{u_A(K^{-1})^{AB}\partial_B}{\sqrt{\kappa_u}}.
```

## 5. One-effective-time constraint

Define the metric-orthogonal projector transverse to the orientation `u`:

```math
(P_\perp)^A{}_B
=
\delta^A{}_B
-
\frac{u^A u_B}{u_Cu^C},
```

with indices raised and lowered using `K`.

The stability constraint is

```math
(P_\perp)^A{}_B\,\partial_A\phi=0.
```

Equivalently,

```math
\partial_A\phi
\propto
u_A.
```

Therefore the field may evolve along the temporal orientation but has no independent gradients along the two transverse temporal directions.

Locally,

```math
\phi
=
\phi(s_T,\mathbf X_9).
```

## 6. Reduced stable kinetic term

Under the constraint, the temporal kinetic term reduces to a single positive contribution:

```math
\frac12(K^{-1})^{AB}
\partial_A\phi\,\partial_B\phi
=
\frac12(D_u\phi)^2.
```

The effective Lagrangian becomes

```math
\mathcal L_{\mathrm{eff}}
=
\frac12(D_u\phi)^2
-\frac12|\nabla_9\phi|^2
-V(\phi).
```

The corresponding effective Hamiltonian density is

```math
\mathcal H_{\mathrm{eff}}
=
\frac12\Pi_u^2
+\frac12|\nabla_9\phi|^2
+V(\phi),
```

which is bounded below when `V` is bounded below.

## 7. Consequence for TVT ontology

The provisional interpretation is now:

1. temporal space has three physical directions;
2. a system possesses an orientation in that space;
3. only the oriented combination acts as its local dynamical clock;
4. the two transverse temporal directions encode possible rotations, sector relations, and hidden orientation, rather than independent unconstrained evolution;
5. different systems may follow different effective temporal directions.

This preserves the physical role of all three temporal dimensions while avoiding three independent clocks for a single field.

## 8. Observable and dark sectors

Visible matter has

```math
\mathbf u_T\approx(1,0,0),
```

so its effective clock is approximately `tau`.

A hidden-sector excitation may have

```math
\mathbf u_T\approx(0,1,0)
```

or

```math
\mathbf u_T\approx(0,0,1),
```

or a mixed hidden orientation.

Each excitation still has one effective local time. What differs is the direction of that time within the complete temporal space.

This gives a sharper meaning to a dark sector:

> A dark excitation is not necessarily a field evolving simultaneously through extra clocks. It is a field whose single effective evolution direction is poorly aligned with the visible temporal axis.

## 9. Coupled temporal metric

For the symmetric metric `K(epsilon)`, the inverse is

```math
K^{-1}
=
\frac{1}{1-\varepsilon}I_3
-
\frac{\varepsilon}{(1-\varepsilon)(1+2\varepsilon)}J_3,
```

where `J_3` is the all-ones matrix.

Therefore

```math
\kappa_u
=
\frac{u\cdot u}{1-\varepsilon}
-
\frac{\varepsilon(u_\tau+u_\sigma+u_\rho)^2}
{(1-\varepsilon)(1+2\varepsilon)}.
```

Within

```math
-\frac12<\varepsilon<1,
```

`kappa_u` remains positive for every nonzero orientation. The effective clock can therefore be normalized throughout the allowed geometric interval.

## 10. What remains unresolved

The one-effective-time constraint solves only the first classical instability of the toy scalar model. It does not yet prove:

- quantum unitarity;
- causal consistency between differently oriented systems;
- a well-posed global initial-value problem;
- stability of vector, spinor, or gravitational fields;
- a dynamical origin for the constraint;
- a gauge symmetry that enforces the constraint;
- consistency when temporal orientation varies across spacetime.

The next theoretical goal is to derive the constraint from an action rather than impose it manually.

## Provisional stability principle

> Physical systems inhabit a three-dimensional temporal orientation space but propagate dynamically along only one effective temporal direction at each event. Transverse temporal derivatives are constrained, preventing the additional temporal directions from becoming independent negative-energy clocks.
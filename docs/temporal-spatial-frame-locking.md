# Temporal–Spatial Frame Locking

## Status

This document records a central provisional hypothesis of Temporal Vector Theory (TVT): a temporal orientation does not select only an effective clock. It also selects the associated effective spatial triad.

The proposal is exploratory and must eventually be derived from a covariant action rather than imposed by definition.

## 1. Three temporal directions and three spatial triads

Let the complete temporal basis be

```math
\{\mathbf e_\tau,\mathbf e_\sigma,\mathbf e_\rho\},
```

and let each temporal direction be paired with one spatial triad:

```math
\tau\leftrightarrow
\{\mathbf e_{\tau1},\mathbf e_{\tau2},\mathbf e_{\tau3}\},
```

```math
\sigma\leftrightarrow
\{\mathbf e_{\sigma1},\mathbf e_{\sigma2},\mathbf e_{\sigma3}\},
```

```math
\rho\leftrightarrow
\{\mathbf e_{\rho1},\mathbf e_{\rho2},\mathbf e_{\rho3}\}.
```

The pure sectors are therefore

```math
\mathcal S_\tau^{3,1},\qquad
\mathcal S_\sigma^{3,1},\qquad
\mathcal S_\rho^{3,1}.
```

## 2. Effective temporal direction

A physical excitation carries one normalized temporal orientation

```math
\mathbf u_T=(u_\tau,u_\sigma,u_\rho),
```

with

```math
u_\tau^2+u_\sigma^2+u_\rho^2=1.
```

This orientation defines its single local effective clock.

## 3. Effective spatial triad

The same temporal orientation selects three effective spatial basis vectors:

```math
\mathbf E_i(\mathbf u_T)
=
u_\tau\mathbf e_{\tau i}
+u_\sigma\mathbf e_{\sigma i}
+u_\rho\mathbf e_{\rho i},
\qquad i=1,2,3.
```

A physical position available to that excitation is then

```math
\mathbf X_{\mathrm{phys}}
=q^1\mathbf E_1
+q^2\mathbf E_2
+q^3\mathbf E_3.
```

Thus a system has only three local spatial coordinates even though the complete spatial manifold has nine fundamental directions.

## 4. Frame-locking principle

The provisional principle is:

> The effective temporal direction and the effective spatial triad form one locked local 3+1 frame. A change in temporal orientation rotates the accessible spatial triad with it.

Symbolically,

```math
\mathbf u_T
\longrightarrow
\mathcal S^{3,1}(\mathbf u_T).
```

The temporal and spatial sectors are therefore not chosen independently.

## 5. Pure-sector limits

For visible matter,

```math
\mathbf u_T=(1,0,0),
```

so

```math
\mathbf E_i=\mathbf e_{\tau i}.
```

For a pure sigma-sector excitation,

```math
\mathbf u_T=(0,1,0),
```

so

```math
\mathbf E_i=\mathbf e_{\sigma i}.
```

For a pure rho-sector excitation,

```math
\mathbf u_T=(0,0,1),
```

so

```math
\mathbf E_i=\mathbf e_{\rho i}.
```

Mixed orientations define mixed local 3+1 sections rather than unrestricted motion across all nine spatial axes.

## 6. Relative velocity as temporal tilt

For the visible sector, the original TVT kinematic parameterization is

```math
u_\tau=\sqrt{1-\frac{v^2}{c^2}},
```

```math
u_\sigma=\frac vc\cos\varphi,
\qquad
u_\rho=\frac vc\sin\varphi.
```

Therefore

```math
\frac{v^2}{c^2}
=u_\sigma^2+u_\rho^2.
```

Relative spatial velocity measures the tilt of the effective temporal direction away from the observer's temporal axis.

Because of frame locking, the same tilt also rotates the spatial triad occupied by the moving system.

## 7. Gravity as frame torsion or transport

Let the temporal orientation be a local field

```math
\mathbf u_T=\mathbf u_T(x).
```

In a gravitational environment,

```math
\nabla_\mu\mathbf u_T\neq0.
```

The local temporal rail is then transported or rotated across spacetime. Because the spatial triad depends on `u_T`,

```math
\nabla_\mu\mathbf E_i
=
\frac{\partial\mathbf E_i}{\partial u_A}
\nabla_\mu u_A
+\text{basis-connection terms}.
```

Thus gravity may be represented not only as curvature of a fixed 3+1 spacetime, but as curvature or torsion of the local locked temporal–spatial frame.

## 8. Velocity and gravity act on the same geometric object

Velocity and gravity need not be unrelated mechanisms.

- Relative velocity changes the orientation of the local frame with respect to an observer.
- Gravity changes how that orientation is transported from event to event.

Both affect

```math
\mathcal S^{3,1}(\mathbf u_T).
```

This gives the causal chain

```math
\text{velocity, gravity, or energy}
\longrightarrow
\delta\mathbf u_T
\longrightarrow
\delta\mathbf E_i
\longrightarrow
\text{changed local 3+1 geometry}.
```

## 9. Matter distribution consequence

Matter remains confined to the three effective axes selected by its temporal orientation.

When gravity or velocity rotates `u_T`, matter does not jump freely into six extra spatial directions. Instead, its full accessible triad rotates continuously inside the nine-dimensional spatial manifold.

This is analogous to a train remaining on a rail while the rail itself bends.

## 10. Interaction overlap

Two systems with orientations `u` and `v` have effective triads

```math
\mathbf E_i(\mathbf u),
\qquad
\mathbf E_i(\mathbf v).
```

Their non-gravitational interaction strength may depend on the overlap of these local frames. A minimal isotropic ansatz is

```math
\mathbf E_i(\mathbf u)\cdot\mathbf E_j(\mathbf v)
\propto
(\mathbf u\cdot\mathbf v)\delta_{ij}.
```

Defining

```math
\chi_{uv}=\mathbf u\cdot\mathbf v,
```

large `chi` corresponds to strongly shared spatial sections, while small `chi` corresponds to weak overlap and dark behavior.

## 11. Important caution

The current equations are a geometric ansatz, not yet a complete dynamics.

The theory still must establish:

- a covariant connection that transports the locked 3+1 frames;
- whether the locking relation follows from symmetry or a constraint;
- recovery of Lorentz invariance in the visible sector;
- recovery of gravitational time dilation and geodesic motion;
- whether frame rotation creates observable deviations from general relativity;
- stability when `u_T` varies rapidly;
- compatibility with the equivalence principle.

## Provisional frame-locking principle

> Each physical excitation propagates within one local 3+1 section of the complete 9+3 manifold. Its temporal orientation selects both its effective clock and its accessible spatial triad. Velocity, gravity, and other interactions may rotate or transport this locked frame, changing both temporal projection and spatial occupation together.

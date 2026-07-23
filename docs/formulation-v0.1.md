# Temporal Vector Theory v0.2

## Abstract

Temporal Vector Theory (TVT) is an exploratory framework in which fundamental time is represented as a three-dimensional orientation space. A physical system does not experience three independent clocks. It follows one effective temporal direction, specified by a normalized vector and two angular coordinates, and experiences one proper-time flow along that direction.

```math
\mathbf n_T=(n_0,n_-,n_+),
\qquad
\|\mathbf n_T\|^2=1.
```

The central component `n_0` measures overlap with the temporal direction associated with our visible sector. The components `n_-` and `n_+` span a hidden temporal plane with opposite provisional polarities.

## Angular parametrization

```math
n_0=\cos\theta,
```

```math
n_-=\sin\theta\cos\phi,
\qquad
n_+=\sin\theta\sin\phi.
```

Therefore,

```math
n_0^2+n_-^2+n_+^2=1.
```

The angle `θ` measures inclination away from the central visible direction. The angle `φ` specifies orientation inside the hidden temporal plane.

The theory therefore proposes:

```math
\text{one effective clock}+\text{two internal temporal angles}.
```

## Relation to proper time

Measured proper time is the one-dimensional evolution parameter along the selected temporal direction. The three-dimensional temporal manifold describes possible orientations of that evolution, not three simultaneous readings of time.

A worldline may be written schematically as

```math
\frac{dX^A}{d\tau}=U^A,
```

where `τ` is one proper-time parameter and the temporal part of `U^A` is oriented by `\mathbf n_T`.

## Kinematic orientation

For the minimal relativistic reinterpretation,

```math
n_0=\sqrt{1-\frac{v^2}{c^2}}=\cos\theta,
```

```math
n_- = \frac vc\cos\phi,
\qquad
n_+ = \frac vc\sin\phi.
```

Hence

```math
\sin\theta=\frac vc.
```

This recovers the standard Lorentz factor:

```math
\gamma=\frac{1}{\cos\theta}.
```

For a massive particle,

```math
E=\frac{mc^2}{\cos\theta},
\qquad
p=mc\tan\theta,
```

so that

```math
E^2=m^2c^4+p^2c^2.
```

This remains a geometric reinterpretation of established relativity, not a new prediction.

## Internal matter orientation versus motion

The theory must distinguish two roles:

- `\mathbf n_T`: a stable or slowly varying internal orientation associated with matter sector identity;
- `\mathbf u_T`: a kinematic and gravitational temporal direction associated with transport and motion.

They may coincide in simple states but must not be identified automatically.

## Locked spatial section

Each temporal direction is hypothesized to select one effective spatial triad:

```math
\mathbf E_i(\mathbf n_T)
=
n_0\mathbf e_{0i}
+n_-\mathbf e_{-i}
+n_+\mathbf e_{+i}.
```

A system therefore occupies one effective local `3+1` section:

```math
\text{temporal direction}\longleftrightarrow\text{effective spatial triad}.
```

Observable spatial sectors are interpreted as orientation-selected projections of a complete geometry, rather than dimensions being created separately for each sector.

## Central overlap, hiddenness, and temporal charge

Define

```math
N_T=n_0^2=\cos^2\theta,
```

```math
H_T=n_-^2+n_+^2=\sin^2\theta,
```

with

```math
N_T+H_T=1.
```

The signed temporal charge is

```math
q_T=n_+^2-n_-^2
=-\sin^2\theta\cos(2\phi).
```

`H_T` measures how far the state lies from our central sector. `q_T` distinguishes positive and negative hidden orientation. A state can have `q_T=0` while still being completely hidden, so temporal charge and visibility are independent descriptors.

## Electromagnetic overlap hypothesis

For orthogonal sector triads, the visible projection amplitude is minimally

```math
\mathcal A_\gamma\propto n_0=\cos\theta.
```

This motivates

```math
e_{\rm eff}=e\cos\theta,
\qquad
\alpha_{\rm eff}=\alpha\cos^2\theta.
```

The hydrogen binding scale then becomes

```math
E_H(\theta)=13.6\cos^4\theta\ {\rm eV}.
```

This is a model hypothesis to be derived from a covariant gauge-field action. It is not yet established.

## Matter sectors

The provisional classification is:

- **central visible matter:** `N_T≈1`;
- **negative dark matter:** `H_T≈1` and `q_T<0`;
- **positive dark matter:** `H_T≈1` and `q_T>0`;
- **balanced dark matter:** `H_T≈1` and `q_T≈0`;
- **mixed matter:** intermediate overlap and charge.

The positive and negative labels do not imply negative mass, negative energy, reverse time, or reversed local causality.

## Primordial interpretation

The complete temporal geometry is provisionally assumed to exist in the primordial state. At high temperature no orientation need be preferred. Cosmological cooling may alter an orientation potential, produce symmetry breaking, select stable local directions, and freeze their relative abundances when orientation-changing reactions fall below the expansion rate:

```math
\Gamma_{\rm orient}(T_*)\approx H(T_*).
```

Thus observable `3+1` sectors emerge dynamically from orientation and frame locking rather than being individually created during the Big Bang.

## Scientific requirements

A viable form of TVT must:

1. reproduce confirmed predictions of special relativity;
2. admit a covariant extension compatible with gravitation;
3. avoid unstable degrees of freedom, ghosts, and uncontrolled negative-energy modes;
4. derive rather than merely fit its electromagnetic overlap law;
5. derive primordial orientation abundances from a dynamical potential and reaction rates;
6. produce at least one prediction not already contained in established theories;
7. allow clear experimental or observational falsification.

## Status

Version 0.2 is a conceptual research scaffold. It is not yet a complete theory, a field theory, or a replacement for relativity or quantum field theory.
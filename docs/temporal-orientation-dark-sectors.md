# Temporal Orientation and Dark-Sector Abundance

## Status

This document records a provisional consequence of Temporal Vector Theory (TVT): if temporal orientation is fundamental, then the two hidden temporal directions may support two fundamental dark sectors and a continuous family of mixed hidden orientations.

This is a speculative model, not an established explanation of dark matter or dark energy.

## 1. Three temporal directions

Let the normalized temporal-orientation vector be

```math
\mathbf u_T=(u_\tau,u_\sigma,u_\rho),
\qquad
u_\tau^2+u_\sigma^2+u_\rho^2=1.
```

The three pure orientations are

```math
\mathbf e_\tau=(1,0,0),
\qquad
\mathbf e_\sigma=(0,1,0),
\qquad
\mathbf e_\rho=(0,0,1).
```

The `tau` orientation defines the visible sector. The `sigma` and `rho` orientations define two fundamental hidden sectors.

## 2. Two dark sectors

The simplest sector assignment is

```math
\mathcal D_\sigma \leftrightarrow \mathbf e_\sigma,
\qquad
\mathcal D_\rho \leftrightarrow \mathbf e_\rho.
```

These sectors may contain distinct dark-matter components,

```math
\rho_{\mathrm{DM}}
=
\alpha_\sigma\rho_{m,\sigma}
+
\alpha_\rho\rho_{m,\rho},
```

and distinct geometric or vacuum-energy components,

```math
\rho_{\mathrm{DE}}
=
\rho_{g,\sigma}
+
\rho_{g,\rho}
+
\rho_{g,\sigma\rho}.
```

The last term represents energy associated with the coupling or relative geometry between the two hidden sectors.

## 3. Continuous hidden orientations

The two hidden directions span a circle of pure dark orientations:

```math
\mathbf u_D(\varphi)
=
(0,\cos\varphi,\sin\varphi).
```

Thus the theory contains two fundamental hidden axes but potentially a continuum of mixed dark states. The pure `sigma` and `rho` sectors are limiting orientations rather than necessarily the only dark species.

## 4. Orientation-controlled coupling

For two systems with temporal orientations `u_A` and `u_B`, define the alignment

```math
\chi_{AB}=\mathbf u_A\cdot\mathbf u_B.
```

A minimal interaction ansatz is

```math
C_{AB}=g_{AB}F(\chi_{AB}),
```

where `F` is a coupling law to be determined. Electromagnetic coupling may be strongly suppressed near temporal orthogonality, while gravitational coupling may depend on the full twelve-dimensional stress-energy rather than only on visible-sector alignment.

## 5. Why dark abundance may exceed visible abundance

A visible state is assumed to occupy a narrow polar region around the `tau` axis, while hidden states occupy most of temporal-orientation space.

Parameterize the temporal sphere by

```math
u_\tau=\cos\theta,
\qquad
u_\sigma=\sin\theta\cos\varphi,
\qquad
u_\rho=\sin\theta\sin\varphi.
```

Define visible orientations by

```math
u_\tau\geq\mu,
\qquad 0\leq\mu\leq1.
```

For a uniform distribution on the forward temporal hemisphere, the visible orientation fraction is the normalized spherical-cap area

```math
f_{\mathrm{vis}}=1-\mu.
```

The hidden fraction is therefore

```math
f_{\mathrm{hidden}}=\mu.
```

Equivalently, if the visible cone has half-angle `theta_c`,

```math
\mu=\cos\theta_c,
```

then

```math
f_{\mathrm{vis}}=1-\cos\theta_c.
```

This is not yet a prediction because `mu` or `theta_c` must be derived dynamically rather than fitted.

## 6. Equal hidden-sector split

If the hidden plane is symmetric under

```math
\sigma\leftrightarrow\rho,
```

then the first-order expectation is

```math
f_\sigma=f_\rho=\frac{f_{\mathrm{hidden}}}{2}.
```

A broken symmetry allows

```math
f_\sigma\neq f_\rho,
```

which could produce two dark components with different clustering or cosmological behavior.

## 7. Matter versus dark energy

Temporal orientation alone does not automatically distinguish dark matter from dark energy. A second criterion is required.

A provisional separation is:

```math
\text{localized hidden excitations}
\longrightarrow
\text{dark matter},
```

```math
\text{background inter-sector tension or vacuum geometry}
\longrightarrow
\text{dark energy}.
```

The distinction must eventually arise from the twelve-dimensional stress-energy tensor and its effective four-dimensional equation of state.

## 8. Minimal quantitative program

The next calculations should determine:

1. a dynamical probability density `P(u_T)` on temporal-orientation space;
2. the visible-domain boundary from interaction physics rather than observation fitting;
3. the coupling function `F(chi)`;
4. the projected four-dimensional stress-energy tensor;
5. conditions under which hidden excitations cluster like matter;
6. conditions under which inter-sector geometry gives negative effective pressure;
7. whether the model can recover observed dark abundances without excessive free parameters.

## Provisional principle

> Temporal Vector Theory permits two fundamental hidden sectors associated with the `sigma` and `rho` temporal axes. The observed dominance of dark components may arise because visible matter occupies only a restricted region of temporal-orientation space, while hidden orientations occupy most of that space. Dark matter corresponds provisionally to localized hidden-sector excitations, whereas dark energy corresponds to background geometric energy or tension between sectors.
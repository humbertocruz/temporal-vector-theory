# Primordial Polarization Freeze-Out

## Status

This document defines a provisional cosmological route for deriving the abundance of ordinary and dark matter from the evolution of a temporal-polarization field in the early universe.

The central idea is that matter may have formed across a continuous space of temporal polarizations, with the final distribution becoming frozen when inter-sector transitions became slower than cosmic expansion.

This is a speculative research program, not an established cosmological model.

## 1. Polarization field

Let the internal matter-orientation field be

```math
\mathbf n(x)
=
(n_\tau,n_\sigma,n_\rho),
\qquad
\mathbf n\cdot\mathbf n=1.
```

The visible-sector projection is

```math
u=|n_\tau|,
```

and the hidden magnitude is

```math
H=n_\sigma^2+n_\rho^2=1-n_\tau^2.
```

The hidden polarity is

```math
P_T=
\frac{n_\rho^2-n_\sigma^2}
{n_\rho^2+n_\sigma^2},
```

when `H>0`.

## 2. Thermal distribution before freeze-out

At sufficiently high temperature, assume polarization-changing reactions keep the distribution near thermal equilibrium:

```math
P_{\mathrm{eq}}(\mathbf n,T)
=
\frac{1}{Z(T)}
\exp\left[-\frac{V(\mathbf n,T)}{T}\right],
```

with

```math
Z(T)
=
\int d\Omega_T
\exp\left[-\frac{V(\mathbf n,T)}{T}\right].
```

The potential may depend on temperature because the early universe changes phase as it cools.

## 3. Minimal finite-temperature potential

A first symmetric ansatz is

```math
V(\mathbf n,T)
=
A(T)(1-n_\tau^2)
+
B(T)(n_\rho^2-n_\sigma^2)^2
+
C(T)(1-n_\tau^2)^2.
```

Interpretation:

- `A(T)` controls whether the visible axis or the hidden plane is energetically preferred;
- `B(T)` controls whether mixed hidden polarities or pure `sigma/rho` polarities are preferred;
- `C(T)` controls the width and stability of intermediate states.

This potential preserves the reflection symmetry

```math
\sigma\leftrightarrow\rho,
\qquad
P_T\rightarrow-P_T,
```

unless an additional symmetry-breaking term is introduced.

## 4. Cosmological evolution

The homogeneous polarization field obeys schematically

```math
\ddot{\mathbf n}
+
3\mathcal H\dot{\mathbf n}
+
\Gamma(T)\dot{\mathbf n}
+
\Pi_{\perp}\frac{\partial V}{\partial\mathbf n}
=0,
```

where:

- `mathcal H` is the Hubble expansion rate;
- `Gamma(T)` is the interaction or relaxation rate;
- `Pi_perp` enforces the unit-vector constraint.

The expansion term damps motion in polarization space.

## 5. Freeze-out condition

Polarization transitions remain efficient while

```math
\Gamma_{\mathrm{pol}}(T)\gg\mathcal H(T).
```

Freeze-out occurs near a temperature `T_*` satisfying

```math
\boxed{
\Gamma_{\mathrm{pol}}(T_*)
\approx
\mathcal H(T_*)
}
```

After this point, the polarization distribution can no longer track equilibrium efficiently.

The frozen distribution is approximately

```math
P_*(\mathbf n)
\approx
P_{\mathrm{eq}}(\mathbf n,T_*),
```

possibly modified by non-equilibrium transport.

## 6. Ordinary- and dark-matter abundances

Let `R_vis` be the region in polarization space capable of supporting ordinary atomic matter. Then

```math
f_{\mathrm{ordinary}\mid\mathrm{matter}}
=
\int_{R_{\mathrm{vis}}}
P_*(\mathbf n)\,d\Omega_T.
```

The dark-matter fraction is

```math
f_{\mathrm{dark}\mid\mathrm{matter}}
=
1-f_{\mathrm{ordinary}\mid\mathrm{matter}}.
```

The observational target is approximately

```math
f_{\mathrm{ordinary}\mid\mathrm{matter}}
\approx
\frac{5}{5+27}
=
0.15625.
```

The goal is not to impose this value, but to derive it from `V`, `Gamma_pol`, and the visibility or atomic-stability boundary.

## 7. Why the primordial route is promising

The early universe naturally supplies:

1. high temperatures capable of exploring many polarization states;
2. phase transitions that can reshape the polarization potential;
3. rapid expansion that can freeze a nontrivial distribution;
4. symmetry breaking that can distinguish visible and hidden populations;
5. relic abundances that survive to late cosmological times.

Thus the observed ordinary-to-dark matter ratio could be a relic of the moment when polarization conversion ceased to remain in equilibrium.

## 8. Three possible abundance mechanisms

### 8.1 Geometric freeze-out

If the potential is nearly flat at `T_*`, abundance is dominated by orientation-space volume.

The visible fraction is then approximately the measure of the atomic-stability cone.

### 8.2 Boltzmann-biased freeze-out

If visible states have an energy offset `Delta V`, their abundance is weighted by

```math
f_{\mathrm{vis}}
\propto
\Omega_{\mathrm{vis}}
\exp\left[-\frac{\Delta V}{T_*}\right].
```

A small energetic bias can substantially alter a geometric fraction.

### 8.3 Dynamical trapping

Even if the equilibrium distribution is broad, barriers in `V` may trap states in different polarization basins.

The final fractions then depend on transition rates and domain evolution rather than equilibrium alone.

## 9. Connection to dark energy

The total field energy contains gradient, kinetic, and potential contributions:

```math
\rho_n
=
\frac12|\dot{\mathbf n}|^2
+
\frac{1}{2a^2}|\nabla\mathbf n|^2
+
V(\mathbf n,T).
```

Localized excitations may behave as matter, while residual nearly homogeneous potential energy may contribute an effective vacuum component.

This offers a possible separation:

```math
\text{frozen localized polarization excitations}
\longrightarrow
\text{ordinary and dark matter},
```

```math
\text{residual background polarization energy}
\longrightarrow
\text{candidate dark-energy contribution}.
```

This must eventually reproduce the observed effective equation of state rather than merely relabel vacuum energy.

## 10. First calculable model

The first concrete calculation should reduce the distribution to the visible coordinate

```math
u=|n_\tau|,
```

and choose a minimal potential such as

```math
V(u,T_*)
=
\alpha(1-u^2)
+
\lambda(1-u^2)^2.
```

Then

```math
P_*(u)
=
\frac{1}{Z}
\exp\left[-\frac{V(u,T_*)}{T_*}\right],
```

with `u` uniform in the spherical measure for the forward hemisphere.

For a visible boundary `u_c`, the predicted fraction is

```math
f_{\mathrm{vis}}
=
\frac{
\int_{u_c}^{1}
\exp[-V(u,T_*)/T_*]\,du
}{
\int_0^1
\exp[-V(u,T_*)/T_*]\,du
}.
```

The immediate task is to determine whether simple dimensionless ratios

```math
\frac{\alpha}{T_*},
\qquad
\frac{\lambda}{T_*}
```

can produce a value near `0.15625` without fine tuning.

## 11. Falsification pressure

The primordial mechanism must be rejected or revised if it requires:

- many unrelated fitted parameters;
- unstable ordinary matter after freeze-out;
- excessive interaction between dark and visible sectors;
- unacceptable extra radiation or thermal degrees of freedom;
- conflict with nucleosynthesis or cosmic-background evolution;
- a dark-energy behavior unlike observation.

## Provisional primordial-freeze-out principle

> The present distribution of matter across temporal polarizations may be a relic of the early universe. At high temperature, polarization states were dynamically explored; as expansion overtook polarization-changing interactions, the distribution froze. Ordinary matter then corresponds to the subset of frozen orientations capable of supporting visible-sector atomic structure, while the remaining stable orientations contribute dark matter.

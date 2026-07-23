# Angular Measure as a Cosmological Density Measure

## Status

Exploratory model. The visible-cone angle is derived from the recombination toy model, while the mapping from angular measure to cosmological density is a new hypothesis that must be justified dynamically.

## 1. Angular measure

For a unit temporal-orientation vector on the forward temporal hemisphere,

```math
\mathbf n_T=(\cos\theta,\sin\theta\cos\phi,\sin\theta\sin\phi),
```

the rotationally invariant measure is

```math
d\mu=\sin\theta\,d\theta\,d\phi.
```

After normalization on the hemisphere, the cumulative fraction inside a cone of opening angle `theta` is

```math
F(\theta)=1-\cos\theta.
```

The recombination-based estimate gives

```math
\theta_{\rm vis}\approx18.74^\circ,
\qquad
\cos\theta_{\rm vis}\approx0.9470,
```

and therefore

```math
F_{\rm vis}=1-\cos\theta_{\rm vis}\approx0.05299.
```

This approximately 5.3 percent value was not inserted as an abundance target. It follows from the toy electromagnetic-overlap law and the Saha recombination criterion.

## 2. Minimal density bridge

Suppose that at freeze-out:

1. temporal orientations are populated with uniform comoving energy per unit angular measure;
2. the mean conserved rest-energy per orientation is independent of `theta` before sector-dependent condensation;
3. each angular cell evolves into one effective cosmological component without large later transfer between angular regions.

Then

```math
d\rho=C\,d\mu
```

for a constant `C`, and normalized cosmological density fractions equal normalized angular fractions:

```math
\Omega(A)=\frac{\int_A d\mu}{\int_{\rm hemisphere}d\mu}.
```

Under these assumptions,

```math
\Omega_{\rm central}=1-\cos\theta_{\rm vis}\approx5.30\%.
```

This supplies a mathematically explicit bridge between the visible cone and a density fraction. It is not yet dynamically derived.

## 3. Three angular regimes

A stronger candidate interpretation assigns three equations of state to angular regions:

```math
0\leq\theta<\theta_{\rm vis}
\quad\longrightarrow\quad
\text{central atomic matter},
```

```math
\theta_{\rm vis}\leq\theta<\theta_{\rm vac}
\quad\longrightarrow\quad
\text{hidden massive matter},
```

```math
\theta_{\rm vac}\leq\theta\leq\frac{\pi}{2}
\quad\longrightarrow\quad
\text{vacuum-like temporal field energy}.
```

The corresponding fractions are

```math
\Omega_{\rm central}=1-\cos\theta_{\rm vis},
```

```math
\Omega_{\rm hidden\ matter}=\cos\theta_{\rm vis}-\cos\theta_{\rm vac},
```

```math
\Omega_{\rm vacuum}=\cos\theta_{\rm vac}.
```

These automatically sum to unity.

## 4. A geometric surprise near 45 degrees

The most symmetric candidate boundary in the hemisphere is

```math
\theta_{\rm vac}=45^\circ,
\qquad
\cos\theta_{\rm vac}=\frac{1}{\sqrt2}\approx0.7071.
```

Keeping the independently estimated visible boundary,

```math
\Omega_{\rm central}\approx5.30\%,
```

```math
\Omega_{\rm hidden\ matter}
=0.9470-0.7071
\approx23.99\%,
```

```math
\Omega_{\rm vacuum}
=0.7071
\approx70.71\%.
```

Thus the parameter-free angular split at 45 degrees gives approximately

```math
5.3\% : 24.0\% : 70.7\%.
```

This is qualitatively close to the observed baryonic-matter, dark-matter, and dark-energy pattern, but it is not a quantitative fit and must not be presented as one.

## 5. Reverse-engineered observational boundary

If one instead inserts a target hidden-matter fraction near 26.5 percent after using the derived visible boundary, then

```math
\cos\theta_{\rm vac}
=\cos\theta_{\rm vis}-0.265
\approx0.6820,
```

which gives

```math
\theta_{\rm vac}\approx47.0^\circ.
```

The remaining vacuum fraction is then approximately 68.2 percent. This 47-degree value is fitted to the target composition and is therefore not a prediction.

The closeness between 45 degrees and 47 degrees motivates searching for a dynamical transition near equal central and hidden amplitudes:

```math
\cos^2\theta\approx\sin^2\theta.
```

## 6. Candidate physical interpretation of the second boundary

At

```math
\theta=45^\circ,
```

the central and hidden magnitudes are equal:

```math
N_T=\cos^2\theta=\frac12,
\qquad
H_T=\sin^2\theta=\frac12.
```

A possible phase rule is:

- `N_T > H_T`: localized massive excitations remain dynamically stable;
- `N_T < H_T`: energy is dominated by collective temporal-field stress and develops a vacuum-like equation of state;
- `N_T = H_T`: critical boundary between the two regimes.

This rule is attractive because it introduces no new numerical scale. It remains speculative until derived from a Lagrangian and its stress-energy tensor.

## 7. Required derivation

The next mathematical target is a field model whose equation-of-state parameter depends on temporal inclination:

```math
w(\theta)=\frac{p(\theta)}{\rho(\theta)}.
```

A successful model should produce approximately

```math
w\approx0
```

for the intermediate hidden massive region and

```math
w\approx-1
```

for the large-angle region, with a transition naturally near `theta = 45 degrees`.

Only after this is derived can the angular fractions be interpreted as baryonic matter, dark matter, and dark energy rather than merely as a suggestive geometric partition.

# First Polarization-Abundance Model

## Status

This document records the first quantitative toy model connecting continuous temporal polarization to the observed split between ordinary matter and dark matter.

It is not yet a prediction. The present numerical thresholds are inferred from observed abundances under deliberately simple assumptions and must later be derived from dynamics.

## 1. Cosmological bookkeeping

Use the approximate composition

```math
5\%\ \text{ordinary matter}
+27\%\ \text{dark matter}
+68\%\ \text{dark energy}.
```

The matter-only fraction is therefore

```math
f_{\mathrm{matter}}=0.05+0.27=0.32.
```

The fraction of ordinary matter within the matter sector is

```math
f_{\mathrm{vis}\mid\mathrm{matter}}
=
\frac{0.05}{0.32}
=
0.15625.
```

Hence

```math
f_{\mathrm{dark}\mid\mathrm{matter}}=0.84375.
```

## 2. Uniform orientation model

Let

```math
u=|n_\tau|,
\qquad
0\leq u\leq1,
```

where `u=1` is fully aligned with the visible temporal-spatial section and `u=0` is fully contained in the hidden plane.

For a uniform distribution of orientations over a forward temporal hemisphere, `u` is uniform on `[0,1]`.

Define ordinary matter by

```math
u\geq u_c.
```

Then

```math
f_{\mathrm{vis}\mid\mathrm{matter}}=1-u_c.
```

Matching the observed matter-only ordinary fraction gives

```math
u_c=1-0.15625=0.84375.
```

Therefore the first inferred threshold is

```math
\boxed{|n_\tau|\geq0.84375}
```

for ordinary matter, and

```math
\boxed{|n_\tau|<0.84375}
```

for dark or partially dark matter.

## 3. Angular form

Using

```math
n_\tau=\cos\theta,
```

the threshold angle is

```math
\theta_c=\arccos(0.84375)\approx32.46^\circ.
```

Thus ordinary matter occupies a narrow cone around the visible temporal axis in this toy geometry.

## 4. Visible-sector consistency

Define

```math
q=n_\tau^2.
```

The threshold becomes

```math
q_c=(0.84375)^2\approx0.7119.
```

So the model provisionally classifies matter as ordinary only when at least about `71.2%` of its temporal-spatial consistency projects into the visible section.

## 5. Provisional polarization bands

A simple partition is:

| Class | Range of `u=|n_tau|` | Fraction of matter | Fraction of total cosmic budget |
|---|---:|---:|---:|
| Almost decoupled | `0` to `0.20` | `20%` | `6.4%` |
| Strongly dark | `0.20` to `0.60` | `40%` | `12.8%` |
| Weakly dark | `0.60` to `0.84375` | `24.375%` | `7.8%` |
| Ordinary matter | `0.84375` to `1` | `15.625%` | `5%` |

These bands are illustrative and not fundamental.

## 6. Electromagnetic-overlap law

Assume

```math
\mathcal V(q)=q^p.
```

If the visibility at the inferred threshold is required to be `1%`,

```math
\mathcal V(q_c)=0.01,
```

then

```math
p=
\frac{\ln(0.01)}{\ln(0.7119)}
\approx13.55.
```

Equivalently,

```math
\mathcal V(n_\tau)
\approx
|n_\tau|^{27.1}.
```

This is a very steep overlap law. It should not be adopted as fundamental unless a microscopic mechanism derives such nonlinearity.

## 7. Hidden temporal polarity

Define the hidden-polarity coordinate

```math
P_T=
\frac{n_\rho^2-n_\sigma^2}
{n_\rho^2+n_\sigma^2},
```

when the hidden magnitude is nonzero.

Under exact `sigma-rho` symmetry, the total dark-matter abundance splits equally on average between positive and negative polarity.

If a mixed band is provisionally defined by

```math
|P_T|<0.2,
```

then a uniform hidden-plane angular distribution gives an illustrative division near

```math
11.77\%\ \text{negative-polarity dark matter},
```

```math
3.46\%\ \text{mixed-polarity dark matter},
```

```math
11.77\%\ \text{positive-polarity dark matter},
```

as fractions of the total cosmic budget.

## 8. What has and has not been derived

This model derives the geometric threshold required by the observed matter split under uniform orientation.

It does not explain why:

- the polarization distribution is uniform;
- the threshold is `u_c=0.84375`;
- the electromagnetic overlap falls so steeply;
- the visible sector contains the observed abundance;
- the dark-energy fraction is about `68%`.

Those quantities must be sought from independent physical origins.

## 9. Independent derivation program

The target numbers should be attacked from:

1. geometry of temporal-orientation space;
2. the polarization potential;
3. stability of localized matter excitations;
4. atomic binding and chemistry;
5. photon coupling and gauge overlap;
6. primordial-universe evolution and polarization freeze-out.

Agreement between two or more independent derivations would be far more significant than fitting the abundance directly.

## Provisional result

> Under a uniform forward-hemisphere distribution, the observed ratio of ordinary to total matter corresponds to `|n_tau| >= 0.84375`, or a visible cone of approximately `32.46 degrees`. This is an inferred benchmark, not yet a fundamental prediction.

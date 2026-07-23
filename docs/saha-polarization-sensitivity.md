# Sensitivity of the Saha-Based Polarization Threshold

## Status

This note tests whether the provisional Saha-based visible-sector threshold is robust under changes in temperature and ionization fraction. It is a toy-model sensitivity study, not a precision recombination calculation.

## Assumptions

- Polarization coordinate: `u = |n_tau|`.
- Effective charge: `e_eff = e u`.
- Effective fine-structure constant: `alpha_eff = alpha u^2`.
- Hydrogen binding energy: `E_H(u) = 13.6 u^4 eV`.
- Baryon-to-photon ratio: `eta = 6.1e-10`.
- Hydrogen number density approximated by `n_H = eta n_gamma(T)`.
- Saha equilibrium used to infer the binding energy required for a chosen ionization fraction `x_e`.

The Saha relation is

```math
\frac{x_e^2}{1-x_e}
=
\frac{1}{n_H}
\left(\frac{2\pi m_e k_B T}{h^2}\right)^{3/2}
\exp\left(-\frac{E_{\rm crit}}{k_B T}\right).
```

Solving for the required binding energy gives

```math
E_{\rm crit}(T,x_e)
=
k_B T
\ln\left[
\frac{1}{n_H}
\left(\frac{2\pi m_e k_B T}{h^2}\right)^{3/2}
\frac{1-x_e}{x_e^2}
\right].
```

The polarization threshold is then

```math
u_c
=
\left(\frac{E_{\rm crit}}{13.6\,\mathrm{eV}}\right)^{1/4}.
```

## Numerical sensitivity

Representative values are:

| T (K) | x_e | E_crit (eV) | u_c | theta_c |
|---:|---:|---:|---:|---:|
| 2500 | 0.1 | 9.99 | 0.926 | 22.2 deg |
| 2500 | 0.5 | 9.17 | 0.906 | 25.0 deg |
| 2500 | 0.9 | 8.57 | 0.891 | 27.0 deg |
| 2800 | 0.1 | 11.15 | 0.952 | 17.9 deg |
| 2800 | 0.5 | 10.23 | 0.931 | 21.3 deg |
| 2800 | 0.9 | 9.56 | 0.916 | 23.7 deg |
| 3000 | 0.1 | 11.92 | 0.968 | 14.6 deg |
| 3000 | 0.5 | 10.94 | 0.947 | 18.7 deg |
| 3000 | 0.9 | 10.22 | 0.931 | 21.4 deg |
| 3200 | 0.1 | 12.69 | 0.983 | 10.6 deg |
| 3200 | 0.5 | 11.64 | 0.962 | 15.9 deg |
| 3200 | 0.9 | 10.87 | 0.946 | 19.0 deg |
| 3500 | 0.5 | 12.69 | 0.983 | 10.6 deg |
| 3500 | 0.9 | 11.85 | 0.966 | 14.9 deg |

At 3500 K with `x_e = 0.1`, the required binding energy exceeds 13.6 eV, so even fully aligned ordinary hydrogen would not yet satisfy that ionization criterion in this simplified equilibrium treatment.

## Main result

Across the central range

```math
2800\,\mathrm{K}\lesssim T\lesssim3200\,\mathrm{K},
\qquad
0.1\lesssim x_e\lesssim0.9,
```

the threshold lies approximately in

```math
0.916\lesssim u_c\lesssim0.983.
```

For the narrower and more representative region around `x_e = 0.5`,

```math
0.931\lesssim u_c\lesssim0.962.
```

Thus the earlier central estimate

```math
u_c\approx0.947,
\qquad
\theta_c\approx18.7^\circ
```

is not an isolated numerical accident. It remains within a relatively narrow high-alignment band under reasonable variation of the toy-model inputs.

## Primordial bias required for the observed matter ratio

Using the frozen distribution

```math
P(u)\propto\exp[-a(1-u^2)],
```

and requiring

```math
f_{\rm vis}=\frac{5}{5+27}=0.15625,
```

the required order-unity bias varies with the threshold.

Examples:

| T (K) | x_e | u_c | required a |
|---:|---:|---:|---:|
| 2500 | 0.5 | 0.906 | 0.96 |
| 2800 | 0.5 | 0.931 | 1.57 |
| 3000 | 0.5 | 0.947 | 2.11 |
| 3200 | 0.5 | 0.962 | 2.89 |
| 3500 | 0.5 | 0.983 | 5.68 |

For the central recombination range, the required bias is generally of order unity rather than exponentially or hierarchically large.

## Interpretation

The Saha-based mechanism does not uniquely predict the observed abundance yet, because the temperature history, nonequilibrium recombination dynamics, and primordial polarization potential remain independent inputs.

However, it supports three provisional conclusions:

1. atomic visibility requires strong alignment with the visible temporal sector;
2. a threshold near `u_c ~ 0.94-0.96` is reasonably stable in the central toy-model range;
3. reproducing the visible-to-dark matter ratio then requires only an order-unity primordial preference for the visible sector.

## Next corrections

A serious calculation must replace equilibrium Saha treatment with a recombination rate equation including expansion, photon escape, excited hydrogen states, and polarization-dependent reaction rates.

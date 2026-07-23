# Recombination-derived visible cone

## Status

This document records a toy calculation. It combines standard hydrogen recombination physics with the speculative Temporal Vector Theory coupling hypothesis

```math
e_{\rm eff}=e\cos\theta.
```

The observed visible fraction is **not** inserted into the calculation below.

## Temporal-angle coupling

Let the temporal orientation be

```math
\mathbf n_T=(\cos\theta,\sin\theta\cos\phi,\sin\theta\sin\phi).
```

Assume that electromagnetic amplitude is the projection onto the central temporal direction:

```math
e_{\rm eff}=e\cos\theta.
```

Then

```math
\alpha_{\rm eff}=\alpha\cos^2\theta
```

and the hydrogen ground-state binding energy becomes

```math
E_H(\theta)=13.6\cos^4\theta\ {\rm eV}.
```

## Saha criterion

For hydrogen recombination,

```math
\frac{x_e^2}{1-x_e}
=
\frac{1}{n_H}
\left(\frac{2\pi m_e k_B T}{h^2}\right)^{3/2}
\exp\left[-\frac{E_H}{k_B T}\right].
```

Using a baryon-to-photon ratio

```math
\eta=6.1\times10^{-10}
```

and the photon number density

```math
n_\gamma(T)=\frac{2\zeta(3)}{\pi^2}
\left(\frac{k_BT}{\hbar c}\right)^3,
\qquad n_H\approx\eta n_\gamma,
```

one can solve for the binding energy required at a chosen ionization fraction.

For the midpoint criterion

```math
x_e=0.5
```

at

```math
T=3000\ {\rm K},
```

the required binding energy is

```math
E_{\rm crit}\approx10.94\ {\rm eV}.
```

Therefore

```math
13.6\cos^4\theta_c=10.94,
```

which gives

```math
\cos\theta_c\approx0.9470,
```

```math
\theta_c\approx18.74^\circ.
```

## Angular measure

For orientations uniformly distributed over the forward temporal hemisphere, the invariant angular measure is

```math
d\mu=\sin\theta\,d\theta\,d\phi.
```

The fraction inside a cone of half-angle `\theta_c` is

```math
f_{\rm cone}
=
\frac{\int_0^{2\pi}\int_0^{\theta_c}\sin\theta\,d\theta\,d\phi}
{\int_0^{2\pi}\int_0^{\pi/2}\sin\theta\,d\theta\,d\phi}
=1-\cos\theta_c.
```

Using the recombination-derived angle,

```math
f_{\rm cone}=1-0.9470\approx0.05299.
```

Thus the toy model predicts

```math
f_{\rm cone}\approx5.30\%.
```

This is close to the commonly quoted roughly five-percent ordinary-matter share of the total cosmic energy budget, although that cosmological quantity is not identical to the fraction of matter orientations. The numerical proximity is therefore a motivation for further work, not a confirmation.

## Temperature sensitivity

For `x_e=0.5`:

| Temperature | Critical binding energy | `cos(theta_c)` | `theta_c` | Uniform cone fraction |
|---:|---:|---:|---:|---:|
| 2800 K | 10.23 eV | 0.9314 | 21.35 deg | 6.86% |
| 3000 K | 10.94 eV | 0.9470 | 18.74 deg | 5.30% |
| 3200 K | 11.64 eV | 0.9619 | 15.88 deg | 3.81% |

The result remains of order a few percent across this range but is not sharply fixed.

## Interpretation limits

This calculation does not yet derive the present cosmological abundance because:

1. the Saha equation assumes equilibrium;
2. real recombination is a nonequilibrium multi-level process;
3. the orientation distribution may not be uniform;
4. the baryon-to-photon ratio and recombination temperature are imported from standard cosmology;
5. the coupling law `e_eff=e cos(theta)` remains a geometric hypothesis that needs a covariant field-theory derivation;
6. the roughly five-percent ordinary-matter share of the total energy budget includes dark energy in the denominator, whereas the cone fraction is currently a fraction of orientation space.

## Current conclusion

The calculation provides a nontrivial numerical coincidence:

```math
\text{Saha recombination + geometric photon overlap}
\Longrightarrow
\theta_c\approx18.7^\circ
\Longrightarrow
f_{\rm cone}\approx5.3\%.
```

The next required step is a nonequilibrium recombination model and a precise mapping between orientation-space abundance and the cosmological density parameters.

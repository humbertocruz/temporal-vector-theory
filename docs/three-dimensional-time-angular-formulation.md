# Three-Dimensional Time as an Angular Orientation Space

## Core reformulation

Temporal Vector Theory is reformulated around a three-dimensional temporal orientation space rather than three independent clocks.

A physical system experiences one effective proper-time flow. Its temporal state is represented by a unit direction in a three-dimensional internal time space:

```math
\mathbf n_T=(n_0,n_-,n_+),
\qquad
n_0^2+n_-^2+n_+^2=1.
```

The three axes are not three separately measurable times. They are three geometric directions available to the single effective clock.

## Angular parametrization

A unit temporal orientation is specified by two angles:

```math
n_0=\cos\theta,
```

```math
n_-=\sin\theta\cos\phi,
\qquad
n_+=\sin\theta\sin\phi.
```

Therefore:

```math
\mathbf n_T=
(\cos\theta,\sin\theta\cos\phi,\sin\theta\sin\phi).
```

Interpretation:

- `θ` measures departure from the central visible temporal axis;
- `φ` determines orientation inside the hidden positive-negative temporal plane;
- one proper-time parameter remains sufficient for local evolution.

## Central and hidden sectors

The central visible direction is

```math
\theta=0
\quad\Rightarrow\quad
\mathbf n_T=(1,0,0).
```

The hidden equator is

```math
\theta=\frac{\pi}{2}
\quad\Rightarrow\quad
n_0=0.
```

Representative hidden directions are:

```math
\phi=0
\quad\Rightarrow\quad
\mathbf n_T=(0,1,0),
```

for the negative hidden sector, and

```math
\phi=\frac{\pi}{2}
\quad\Rightarrow\quad
\mathbf n_T=(0,0,1),
```

for the positive hidden sector.

Balanced hidden states occur when the positive and negative squared components are equal.

## Centrality, hiddenness, and temporal charge

Define central overlap:

```math
N_T=n_0^2=\cos^2\theta.
```

Define hidden magnitude:

```math
H_T=n_-^2+n_+^2=\sin^2\theta.
```

Then:

```math
N_T+H_T=1.
```

Define temporal orientation charge:

```math
q_T=n_+^2-n_-^2.
```

In angular form:

```math
q_T=-\sin^2\theta\cos(2\phi).
```

`q_T` is a polarity label internal to the orientation space. It does not mean negative energy or backward causal evolution.

## Electromagnetic overlap

For orthogonal central and hidden spatial triads, the simplest projection hypothesis gives

```math
\mathcal A_\gamma\propto n_0=\cos\theta.
```

Thus the effective electromagnetic coupling is provisionally

```math
e_{\mathrm{eff}}=e\cos\theta,
```

and

```math
\alpha_{\mathrm{eff}}=\alpha\cos^2\theta.
```

The hydrogen binding scale then becomes

```math
E_H(\theta)=13.6\cos^4\theta\ \mathrm{eV}.
```

This connects the angular geometry to the earlier Saha-based recombination estimates.

## Angular measure and abundance

Uniform directions on a temporal hemisphere are not uniform in `θ`. The orientation-space measure is

```math
d\mu=\sin\theta\,d\theta\,d\phi.
```

The fraction contained within a central cone of half-angle `θ_c` is

```math
f_{\mathrm{cone}}
=
\frac{\int_0^{2\pi}\int_0^{\theta_c}\sin\theta\,d\theta\,d\phi}
{\int_0^{2\pi}\int_0^{\pi/2}\sin\theta\,d\theta\,d\phi}
=
1-\cos\theta_c.
```

Therefore a 5 percent geometric cone satisfies

```math
1-\cos\theta_c=0.05,
```

which gives approximately

```math
\theta_c\approx18.2^\circ.
```

This is close to the provisional recombination threshold near 18 to 19 degrees found in the simplified Saha analysis. This numerical proximity is recorded as a promising coincidence, not as a derived confirmation.

## Primordial distribution

A non-uniform primordial population may be described by

```math
P(\theta,\phi;T_*)
=
\frac{1}{Z}
\exp\left[-\frac{V(\theta,\phi;T_*)}{T_*}\right].
```

A minimal central-bias potential is

```math
\frac{V(\theta)}{T_*}=a\sin^2\theta.
```

The visible fraction is then

```math
f_{\mathrm{vis}}=
\frac{\int_0^{2\pi}\int_0^{\theta_c}
 e^{-a\sin^2\theta}\sin\theta\,d\theta\,d\phi}
{\int_0^{2\pi}\int_0^{\pi/2}
 e^{-a\sin^2\theta}\sin\theta\,d\theta\,d\phi}.
```

This is the angular equivalent of earlier calculations written using `u=|n_0|=\cos\theta`.

## Conceptual summary

The preferred interpretation is:

> Fundamental time is a three-dimensional orientation space. Matter does not carry three clocks. It follows one effective temporal direction, specified by two internal angles. That direction selects the effective spatial triad and controls overlap with the central electromagnetic sector.

## Scientific status

This is a speculative geometrical reformulation. It becomes physically meaningful only if the angular field, its dynamics, the effective metric, and observable couplings can be derived consistently and tested independently.
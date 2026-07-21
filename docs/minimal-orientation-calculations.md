# Minimal Temporal-Orientation Calculations

## Status

This note begins the first quantitative pass over Temporal Vector Theory (TVT). It deliberately uses the smallest possible model so that each assumption can be identified and later replaced.

The calculations below do not establish dark matter or dark energy. They test whether the proposed orientation geometry can produce useful quantitative relations.

## 1. Temporal orientation space

Let

```math
\mathbf u_T=(u_\tau,u_\sigma,u_\rho),
\qquad
u_\tau^2+u_\sigma^2+u_\rho^2=1.
```

Using spherical coordinates on the forward temporal hemisphere,

```math
u_\tau=\cos\theta,
\qquad
u_\sigma=\sin\theta\cos\varphi,
\qquad
u_\rho=\sin\theta\sin\varphi,
```

with

```math
0\leq\theta\leq\frac{\pi}{2},
\qquad
0\leq\varphi<2\pi.
```

The normalized uniform measure on the forward hemisphere is

```math
dP=\frac{\sin\theta\,d\theta\,d\varphi}{2\pi}.
```

Equivalently, the alignment variable

```math
\chi\equiv u_\tau=\cos\theta
```

is uniformly distributed on

```math
0\leq\chi\leq1
```

under this simplest measure.

## 2. First null result: symmetry alone gives equal quadratic weights

If sector energy is assumed to be proportional only to squared temporal components, then

```math
w_\tau=u_\tau^2,
\qquad
w_\sigma=u_\sigma^2,
\qquad
w_\rho=u_\rho^2.
```

For a uniform orientation distribution,

```math
\langle u_\tau^2\rangle
=
\langle u_\sigma^2\rangle
=
\langle u_\rho^2\rangle
=
\frac13.
```

Therefore, orientation-space symmetry by itself predicts equal average quadratic partition among the three temporal directions.

This does **not** produce a small visible fraction. A visibility rule, a non-uniform probability density, or different projection laws are required.

## 3. Threshold visibility model

Assume visible electromagnetic behavior requires alignment with the visible temporal axis above a threshold

```math
\chi\geq\chi_c,
\qquad
0\leq\chi_c\leq1.
```

Because `chi` is uniform on `[0,1]` in the minimal model,

```math
f_{\mathrm{vis}}
=
\int_{\chi_c}^{1}d\chi
=
1-\chi_c.
```

The hidden fraction is

```math
f_{\mathrm{hidden}}=\chi_c.
```

Using `chi_c=cos(theta_c)`, this is equivalent to

```math
f_{\mathrm{vis}}=1-\cos\theta_c.
```

This result is geometric but is not yet predictive, because `chi_c` must be derived from interaction physics.

## 4. Smooth coupling model

Replace a hard threshold with a smooth visible-sector coupling law

```math
F_n(\chi)=\chi^n,
\qquad n>0.
```

The exponent `n` controls how sharply electromagnetic coupling becomes concentrated near the visible temporal axis.

For a uniform orientation distribution, the average coupling is

```math
\langle F_n\rangle
=
\int_0^1\chi^n\,d\chi
=
\frac{1}{n+1}.
```

Therefore:

```math
n=1\Rightarrow\langle F\rangle=\frac12,
```

```math
n=3\Rightarrow\langle F\rangle=\frac14,
```

```math
n=19\Rightarrow\langle F\rangle=\frac1{20}=0.05.
```

A highly alignment-sensitive law can therefore produce a small average visible coupling without imposing a discontinuous boundary.

This does not imply that the observed visible density equals the mean coupling. It only demonstrates a possible mechanism for suppressing visible-sector interactions over most of orientation space.

## 5. Detection threshold under smooth coupling

Suppose a state is classified as visible when

```math
F_n(\chi)\geq q,
```

where `q` is a minimum detectable coupling fraction.

Then

```math
\chi^n\geq q
```

and therefore

```math
\chi\geq q^{1/n}.
```

The visible orientation fraction becomes

```math
f_{\mathrm{vis}}(n,q)
=
1-q^{1/n}.
```

The hidden fraction is

```math
f_{\mathrm{hidden}}(n,q)
=
q^{1/n}.
```

This separates two physical ideas:

- `n`: how rapidly coupling falls with temporal misalignment;
- `q`: how much coupling is required for a state to behave observably as visible matter.

## 6. Mean alignment in visible and hidden domains

Under the hard-threshold model, visible orientations satisfy `chi in [chi_c,1]`.

Their mean visible-axis alignment is

```math
\langle\chi\rangle_{\mathrm{vis}}
=
\frac{1}{1-\chi_c}
\int_{\chi_c}^{1}\chi\,d\chi
=
\frac{1+\chi_c}{2}.
```

Hidden orientations satisfy `chi in [0,chi_c]`, with

```math
\langle\chi\rangle_{\mathrm{hidden}}
=
\frac{1}{\chi_c}
\int_0^{\chi_c}\chi\,d\chi
=
\frac{\chi_c}{2}.
```

For a five-percent visible cap,

```math
\chi_c=0.95,
```

so

```math
\langle\chi\rangle_{\mathrm{vis}}=0.975,
```

while

```math
\langle\chi\rangle_{\mathrm{hidden}}=0.475.
```

Thus visible states are predicted to be extremely well aligned with the `tau` axis in this toy model.

## 7. Symmetric split of hidden orientations

If the hidden plane is symmetric under exchange

```math
\sigma\leftrightarrow\rho,
```

then any hidden fraction splits equally at first order:

```math
f_\sigma=f_\rho=\frac{f_{\mathrm{hidden}}}{2}.
```

For `f_vis=0.05`,

```math
f_\sigma=f_\rho=0.475.
```

This is not an expected cosmological abundance unless the projection weights and equations of state are also equal. It is only the orientation-space measure.

## 8. Broken hidden-sector symmetry

Introduce an azimuthal probability density

```math
P(\varphi)
=
\frac{1}{2\pi}\left(1+a\cos2\varphi\right),
\qquad |a|<1.
```

The parameter `a` breaks the symmetry between directions preferentially aligned with `sigma` and `rho` while preserving normalization.

A positive `a` favors the `sigma` axis, while a negative `a` favors the `rho` axis.

This provides a minimal one-parameter route to two dark components with unequal abundance.

## 9. Minimal orientation-based interaction ansatz

For two systems `A` and `B`, define

```math
\chi_{AB}=\mathbf u_A\cdot\mathbf u_B.
```

A minimal family of interaction strengths is

```math
g_{AB}^{(n)}
=
g_{AB}^{(0)}|\chi_{AB}|^n.
```

The absolute value keeps the magnitude non-negative while allowing a separate sign or phase factor to encode matter-antimatter distinctions if needed.

At orthogonality,

```math
\chi_{AB}=0
\Rightarrow
g_{AB}^{(n)}=0.
```

At full alignment,

```math
|\chi_{AB}|=1
\Rightarrow
g_{AB}^{(n)}=g_{AB}^{(0)}.
```

The next task is to determine which interactions, if any, should obey this alignment law. Electromagnetism may be strongly orientation-selective, whereas gravity may couple to the full stress-energy tensor.

## 10. What these calculations establish

The minimal calculations give three useful conclusions:

1. Uniform temporal orientation plus quadratic sector weights predicts one-third per sector, so symmetry alone cannot explain a very small visible fraction.
2. A visibility threshold gives the exact geometric relation `f_vis=1-chi_c`.
3. A smooth coupling law `F=chi^n` naturally suppresses visible interaction over most orientation space, with mean coupling `1/(n+1)`.

## 11. Immediate next calculations

The next quantitative steps are:

1. compare threshold and smooth-coupling models;
2. derive a probability density from a temporal-orientation potential rather than assuming uniformity;
3. construct an effective four-dimensional density from twelve-dimensional sector densities and projection coefficients;
4. test whether localized hidden excitations can scale as pressureless matter;
5. test whether inter-sector geometric energy can produce negative effective pressure;
6. verify that the coupling model does not make ordinary matter visibly velocity-dependent in conflict with known relativity.

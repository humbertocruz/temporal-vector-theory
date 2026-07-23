# Temporal Vector Theory

**Temporal Vector Theory (TVT)** is an exploratory hypothesis in which fundamental time is modeled as a three-dimensional orientation space. A physical system does not carry three independent clocks. It follows one effective temporal direction, specified by two internal angles, and experiences one local proper time along that direction.

> This repository develops Temporal Vector Theory as an open, falsifiable, and mathematically explicit research program.

## Central concept

The theory distinguishes a three-dimensional temporal geometry from the one-dimensional clock experienced by matter:

```math
\text{three-dimensional temporal orientation space}
\;\not=\;
\text{three independent clocks}.
```

A normalized temporal direction is written as

```math
\mathbf n_T=(n_0,n_-,n_+),
\qquad
n_0^2+n_-^2+n_+^2=1.
```

Using two angular coordinates,

```math
n_0=\cos\theta,
\qquad
n_-=\sin\theta\cos\phi,
\qquad
n_+=\sin\theta\sin\phi.
```

The angle `θ` measures inclination away from the central visible temporal direction. The angle `φ` specifies orientation within the hidden positive-negative temporal plane.

## One clock, two temporal angles

- Every stable physical system experiences one effective proper-time flow.
- The temporal direction of that flow is a unit vector in a three-dimensional temporal orientation space.
- Two angles determine that direction, just as two angles determine a direction in ordinary three-dimensional space.
- The temporal direction selects a locked effective spatial triad, producing one local `3+1` section.
- The fundamental dimensions are not assumed to be created separately during cosmological evolution; observable `3+1` sectors may emerge through temporal orientation and symmetry breaking.

## Central and hidden sectors

The central visible state is

```math
\mathbf n_T=(1,0,0),
\qquad \theta=0.
```

The two pure hidden orientations are

```math
\mathbf n_T=(0,1,0)
```

and

```math
\mathbf n_T=(0,0,1).
```

They are provisionally called the negative and positive temporal sectors. These labels do not imply negative energy, reverse time, or backward causality.

Define

```math
N_T=n_0^2=\cos^2\theta
```

as the central overlap,

```math
H_T=n_-^2+n_+^2=\sin^2\theta
```

as the hidden magnitude, and

```math
q_T=n_+^2-n_-^2
```

as temporal charge. Thus `θ` controls hiddenness while `φ` controls hidden polarity.

A state may have `q_T=0` while remaining fully hidden, so central visibility and temporal neutrality are distinct concepts.

## Electromagnetic overlap hypothesis

For orthogonal locked spatial triads, the simplest geometric overlap with the visible sector gives

```math
\mathcal A_\gamma\propto n_0=\cos\theta.
```

A minimal effective coupling is therefore

```math
e_{\rm eff}=e\cos\theta,
\qquad
\alpha_{\rm eff}=\alpha\cos^2\theta.
```

This implies the toy hydrogen binding relation

```math
E_H(\theta)=13.6\cos^4\theta\ {\rm eV}.
```

Current recombination estimates in this repository place the transition to ordinary atom-like behavior near `θ≈19°`, subject to more complete nonequilibrium calculations.

## Terminology

- **Temporal orientation**: the full unit vector `\mathbf n_T`.
- **Temporal inclination**: the angle `θ` away from the central sector.
- **Temporal azimuth**: the angle `φ` within the hidden plane.
- **Temporal charge**: `q_T=n_+^2-n_-^2`.
- **Central matter**: matter strongly aligned with `n_0` and electromagnetically visible to us.
- **Positive dark matter**: hidden matter with `q_T>0`.
- **Negative dark matter**: hidden matter with `q_T<0`.
- **Balanced dark matter**: hidden matter with `q_T≈0` but `H_T>0`.

The phrase **temporal spin** may be used informally for the internal direction, but it is not ordinary quantum spin.

## Repository structure

- [`docs/formulation-v0.1.md`](docs/formulation-v0.1.md): initial mathematical formulation
- [`docs/postulates.md`](docs/postulates.md): provisional postulates
- [`docs/three-dimensional-time-angular-model.md`](docs/three-dimensional-time-angular-model.md): central one-clock, two-angle formulation
- [`docs/trigonotime.md`](docs/trigonotime.md): temporal geometry and trigonometry
- [`docs/three-sector-spacetime.md`](docs/three-sector-spacetime.md): candidate complete geometry
- [`docs/complete-space-definition.md`](docs/complete-space-definition.md): provisional definition of the complete manifold
- [`docs/minimal-coupled-metric.md`](docs/minimal-coupled-metric.md): first coupled temporal metric
- [`docs/one-effective-time-constraint.md`](docs/one-effective-time-constraint.md): one-clock stability constraint
- [`docs/temporal-spatial-frame-locking.md`](docs/temporal-spatial-frame-locking.md): locking between temporal orientation and spatial triad
- [`docs/temporal-orientation-dark-sectors.md`](docs/temporal-orientation-dark-sectors.md): dark-sector orientations and abundance model
- [`docs/temporal-polarity.md`](docs/temporal-polarity.md): central, negative, positive, and intermediate states
- [`docs/primordial-polarization-freezeout.md`](docs/primordial-polarization-freezeout.md): primordial freeze-out model
- [`docs/saha-polarization-sensitivity.md`](docs/saha-polarization-sensitivity.md): atom-formation sensitivity calculation
- [`docs/testable-predictions.md`](docs/testable-predictions.md): possible tests and falsification paths
- [`docs/open-problems.md`](docs/open-problems.md): unresolved mathematical and physical issues

## Scientific status

This is a speculative hypothesis under development. It does not replace special relativity, general relativity, or quantum field theory. Established relations are constraints. The model acquires physical value only if it becomes mathematically consistent and produces distinct, falsifiable predictions.

## Authorship

Conceived and iteratively developed by **Humberto Cruz**, in collaboration with artificial intelligence.

---

## Português

A **Teoria Temporal Vetorial** propõe que o tempo fundamental possui uma geometria tridimensional de orientações. A matéria não possui três relógios: ela percorre uma única direção temporal efetiva, determinada por dois ângulos internos. Essa direção seleciona simultaneamente uma tríade espacial efetiva. O ângulo de inclinação controla a sobreposição com nosso setor, enquanto o segundo ângulo distingue orientações temporais positivas, negativas ou balanceadas.
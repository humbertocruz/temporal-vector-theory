# Spherical Temporal Manifold

## Status

This document presents a provisional mathematical formulation for a three-dimensional temporal geometry with cyclic orientation and one effective causal flow. It is a speculative model, not an established physical theory.

## 1. Central hypothesis

Temporal evolution is represented by a vector in a three-dimensional internal temporal space,

\[
\mathbf T=(T_0,T_1,T_2),
\]

while each physical system experiences a single proper-time parameter \(\tau\). The system therefore follows a one-dimensional causal trajectory through a three-dimensional temporal geometry:

\[
\mathbf T=\mathbf T(\tau).
\]

The temporal velocity is

\[
\mathbf u_T=\frac{d\mathbf T}{d\tau}.
\]

We impose the normalization

\[
\mathbf u_T\cdot\mathbf u_T=1.
\]

Therefore the possible directions of temporal evolution form the unit two-sphere:

\[
\mathbf u_T\in S^2.
\]

This sphere is called the **temporal orientation sphere**.

## 2. Angular representation

A temporal orientation is parameterized by two angles,

\[
\mathbf n_T(\theta,\phi)
=
(\cos\theta,\sin\theta\cos\phi,\sin\theta\sin\phi).
\]

The temporal displacement is

\[
d\mathbf T=\mathbf n_T\,d\tau.
\]

Its components are

\[
dT_0=\cos\theta\,d\tau,
\]

\[
dT_1=\sin\theta\cos\phi\,d\tau,
\]

\[
dT_2=\sin\theta\sin\phi\,d\tau.
\]

The proper-time interval is the norm of the temporal displacement:

\[
d\tau^2=dT_0^2+dT_1^2+dT_2^2.
\]

Thus a conventional clock may be interpreted as measuring mainly the central projection \(dT_0\), whereas a hypothetical complete temporal instrument would also measure the hidden components \(dT_1\) and \(dT_2\).

## 3. One causal dimension, three temporal components

The model distinguishes between:

1. the dimension of the temporal state space;
2. the dimension of the experienced causal trajectory.

The temporal state space is three-dimensional, but a physical system follows only one curve through it. This is analogous to a particle moving in three-dimensional space while its path remains one-dimensional.

The total temporal structure is provisionally written as

\[
\mathcal T=\mathbb R_\tau\times S^2_T,
\]

where:

- \(\mathbb R_\tau\) represents monotonic causal progression;
- \(S^2_T\) represents the possible orientations of temporal evolution.

The coordinate \(\tau\) is not a fourth independent temporal direction. It is the parameter that orders points along the trajectory.

## 4. Cyclic temporal orientation

Temporal cyclicity does not need to mean that events repeat. A system may periodically return to the same temporal orientation while continuing forward in proper time.

For example, consider

\[
\theta(\tau)=\theta_0,
\]

\[
\phi(\tau)=\omega_T\tau.
\]

Then

\[
\mathbf n_T(\tau)
=
\left(
\cos\theta_0,
\sin\theta_0\cos\omega_T\tau,
\sin\theta_0\sin\omega_T\tau
\right).
\]

The orientation repeats after the period

\[
P_T=\frac{2\pi}{\omega_T},
\]

so that

\[
\mathbf n_T(\tau+P_T)=\mathbf n_T(\tau).
\]

However,

\[
\tau+P_T\neq\tau.
\]

Therefore the system returns to the same temporal direction but not to the same event.

This distinction is central:

\[
\boxed{
\text{cyclic orientation}\neq\text{closed causal history}
}
\]

## 5. Temporal helix

The complete trajectory may be viewed as a helix in the product space \(\mathbb R_\tau\times S^2_T\). The angular coordinates can repeat while the causal coordinate continues to increase.

A state is written as

\[
X_T(\tau)=\left(\tau,\theta(\tau),\phi(\tau)\right).
\]

Even if

\[
\theta(\tau+P_T)=\theta(\tau)
\]

and

\[
\phi(\tau+P_T)=\phi(\tau)+2\pi,
\]

we still have

\[
X_T(\tau+P_T)\neq X_T(\tau)
\]

because the causal coordinate differs.

This structure permits recurring temporal states without causal loops.

## 6. Dynamical orientation field

The temporal orientation may be promoted to a field,

\[
\mathbf n_T=\mathbf n_T(x),
\]

subject to

\[
\mathbf n_T\cdot\mathbf n_T=1.
\]

A minimal nonlinear sigma-model action is

\[
S_T
=
\int d^4x\sqrt{-g}
\left[
\frac{f_T^2}{2}
\nabla_\mu\mathbf n_T\cdot\nabla^\mu\mathbf n_T
-
V(\mathbf n_T)
\right].
\]

Here:

- \(f_T\) measures the rigidity of the temporal orientation field;
- \(V\) selects dynamically preferred orientations;
- gradients describe spatial or temporal changes in orientation.

The constrained equation of motion is schematically

\[
f_T^2\Box\mathbf n_T
+
\frac{\partial V}{\partial\mathbf n_T}
=
\lambda(x)\mathbf n_T,
\]

where \(\lambda(x)\) enforces the unit-norm condition.

## 7. Matter sectors on the sphere

The temporal sphere can organize the known and hypothetical sectors:

- a visible polar cap near \(\theta=0\);
- an intermediate dark-matter band;
- a hidden-dominated equatorial region;
- the angle \(\phi\) distinguishing temporal polarities.

The provisional electromagnetic overlap with the visible sector is

\[
\mathcal O_{\rm EM}(\theta)=\cos^2\theta.
\]

Thus visibility decreases continuously as the temporal orientation moves away from the central pole.

The previously derived recombination threshold gives an illustrative visible-cone boundary near

\[
\theta_{\rm vis}\approx18.7^\circ.
\]

A possible geometric phase boundary occurs at

\[
\theta_{\rm phase}=45^\circ,
\]

where the central and hidden orientation components are equal:

\[
\cos^2\theta=\sin^2\theta=\frac12.
\]

These boundaries remain provisional and require dynamical derivation.

## 8. Global temporal cycles

A more ambitious possibility is that the average orientation of the universe itself evolves cyclically:

\[
\overline{\mathbf n}_T=\overline{\mathbf n}_T(\tau).
\]

A global cycle could alter the relative abundance or interaction strength of visible, dark and vacuum-like sectors without requiring the universe to return to an earlier causal state.

The cosmological history would then be cyclic in orientation but not necessarily cyclic in entropy, scale factor or event identity.

This provides a possible distinction between:

\[
\text{temporal phase cycles}
\]

and

\[
\text{cosmological recurrence}.
\]

## 9. Avoiding closed timelike curves

The model does not identify proper time periodically:

\[
\tau\not\equiv\tau+P.
\]

Only angular variables are periodic:

\[
\phi\equiv\phi+2\pi.
\]

This avoids automatically generating closed timelike curves. A sufficient provisional condition for causal consistency is

\[
\frac{d\tau}{d\lambda}>0
\]

along every physical worldline parameterized by \(\lambda\).

Temporal orientation may rotate, but causal progression must remain monotonic.

## 10. Observational implications

If temporal orientation varies dynamically, possible signatures include:

1. periodic or quasi-periodic variations in extremely weak hidden-sector couplings;
2. orientation defects or domains in the early universe;
3. dark-sector transitions associated with gradients of \(\mathbf n_T\);
4. gravitational effects shared across differently oriented sectors;
5. partial electromagnetic couplings determined by angular overlap;
6. cosmological cycles in sector abundance without exact repetition of the universe.

No such signature is currently derived quantitatively from this model.

## 11. Open mathematical problems

The next steps are:

1. derive the temporal orientation sphere from a fundamental metric rather than postulating it;
2. determine whether the sphere is a physical manifold, an internal symmetry space or a fiber attached to spacetime;
3. construct a stable potential \(V(\theta,\phi)\);
4. prove the absence of negative-energy modes;
5. couple the orientation field consistently to gravity and matter;
6. distinguish physical orientation changes from ordinary Lorentz boosts;
7. derive observable consequences that differ from conventional dark-matter models;
8. determine whether global orientation cycles can coexist with increasing entropy.

## 12. Provisional statement

> Time is modeled as a three-component vector geometry whose normalized directions form a sphere. Every system experiences one monotonic proper-time trajectory, while the orientation of that trajectory may move cyclically over the temporal sphere. Periodic orientation does not imply repetition of events, because the causal parameter remains non-periodic.

The compact mathematical statement is

\[
\boxed{
\mathcal T=\mathbb R_\tau\times S^2_T,
\qquad
\mathbf n_T(\tau)\in S^2,
\qquad
\frac{d\tau}{d\lambda}>0
}
\]

This is the minimal spherical-temporal formulation of Temporal Vector Theory.
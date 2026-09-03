# The complex of curves pairwise intersecting at most once is contractible in genus two

**Guancheng Pan**

A preprint on Souto's contractibility question for the $1$-curve complex in
genus two.

## The statement

Let `S₂` be the closed orientable surface of genus two. Let `C₁(S₂)` be the flag
simplicial complex whose vertices are the isotopy classes of essential simple
closed curves in `S₂`, a finite set of classes spanning a simplex exactly when
the classes pairwise have geometric intersection number **at most one**.

Souto asked whether `C₁(S)`, or failing that `C_d(S)` for some `d`, is
contractible; the question is disjunctive in the original, and the case `d = 1`
is the one addressed here. The ordinary curve complex `C₀(S)` is famously not
contractible, and Souto's observation is that raising the intersection bound to
one may change that.

> **Theorem.** `C₁(S₂)` is contractible.

The theorem is stated and proved unconditionally, for genus two.

## The method, in one paragraph

The problem is transported to the six-times-marked sphere `Σ = (S², B)` through
the hyperelliptic involution, and the required dictionary — non-separating
curves upstairs correspond to arcs joining two distinct marked points,
separating curves to circles splitting `B` as `3|3` — is proved here rather than
imported, including the isotopy-lifting step that makes it a bijection on
isotopy classes. Two hyperbolic structures are used, and their division of
labour is forced rather than chosen: a hyperbolic **cone metric** of cone angle
`π` on `Σ` pulls back to a *smooth* closed hyperbolic surface upstairs, which is
what makes distinct lifted curves automatically minimal-position closed
geodesics; while a **cusped** metric on `S² ∖ B` is what gives arcs geodesic
representatives with ideal endpoints, and hence a family of arc classes
realising all its pairwise minimal intersection numbers simultaneously. The
intersection number formula `i = 2ĵ + e` relating the two levels is obtained by
squeezing between the two, and the adjacency criterion follows. On the arc side,
Hatcher's arc complex `A(S², B)` is contractible; filtering it by the number of
"bad" vertices — loops, and pairs of arcs sharing an endpoint pair — gives a
spectral sequence whose `E¹` page is the reduced homology of the links of the
strata. The single arithmetic input is that a genus two surface has exactly six
Weierstrass points: it enters as a **budget**, `6 − V′`, which forces every
stratum to contain a complementary region carrying one or two marked points, and
such a region makes the link a cone. Simple connectivity is proved separately,
following Souto, by factoring `C₀ ↪ C₁` through the contractible curve-and-arc
complex of a once-marked surface.

35 pages.

## What this does not settle

- **Genus two only.** The count `6 = 2g + 2` is the budget, and a surface of
  genus `g ≥ 3` has in general no hyperelliptic involution at all, so there is no
  quotient marked sphere and the dictionary has no analogue. The theorem gives
  no information for `g ≥ 3`. See §11.1.
- **The punctured case is not a weaker instance.** The inclusion of the complex
  of a once-punctured surface into that of the closed surface is a simplicial
  retraction, so contractibility of the closed complex implies that of the
  punctured one and not conversely. An argument that assumes the closed case in
  order to derive the punctured case and then recovers the closed case is
  circular.
- **Nothing here is a finite computation.** No homology of a finite subcomplex or
  of a finite quotient poset is computed anywhere, deliberately: for these
  complexes there is in general no map in either direction between such homology
  and the homology of the ambient complex.

Two conventions in §2 do real work and are part of the statement: all arc
representatives are smooth, and a transverse pair is required to meet in a
finite set — the latter is not implied by pointwise transversality, and §2.4
gives a smooth counterexample.

The simple connectivity statement (Theorem 1.3) is proved for every `g ≥ 2`, not
only for genus two; it is the one result here that is not restricted to genus
two. Its proof uses Harer's determination of the homotopy type of `C₀(S_g)`
together with an elementary surgery on an edge, and is unconditional. Souto's
own stronger observation — that `C₀ ↪ C₁` is null-homotopic — is recorded
separately as Proposition 7.8; that one does rest on a contractibility statement
for the arc-and-curve complex whose printed source is the arc version, as
Remark 7.4 explains, and nothing in the paper depends on it.

## Status

This is a preprint. It has not been submitted to a journal and has not been
refereed. No part of it has been machine-checked in a proof assistant, and no
literature comparison beyond an ordinary search has been carried out, so no
claim of novelty or priority is made here.

Corrections, counterexamples and pointers to prior art are all welcome — please
open an issue.

## Licence

Copyright © 2026 Guancheng Pan. Licensed under
[Creative Commons Attribution 4.0 International](LICENSE) (CC BY 4.0): reuse,
redistribute and adapt freely, including commercially, with attribution.

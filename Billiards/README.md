# Billiards Simulations
Both notebooks simulate billiards in a horn: the first shows a horn formed
by two circles that are tangent at their point of intersection, the second shows
a horn for which one side is an arc of a circle and the other a parabola. 

These numerical simulations suggest:
- a.e. (almost every, i.e. up to a set of Lebesgue measure zero) initial
condition starting in a neighborhood of the cusp will eventually be ejected from the horn.
- These trajectories make a finite number of collisions before they are ejected.

Other conjectures:
- There exists an adiabatic invariant: an angular momentum like quantity, the
product of the width of the horn (at a point) and the velocity of the billiard,
is approximately conserved (to first order). 

---

# TODO (simulations):
- This version of the simulations requires that the ray of the trajectory only
intersects the boundary once. We should be more careful when we calculate the
intersection of the ray and the boundary so that we may pick more general curves
for the boundary. 
- For the two circles case, we should simulate the billiards on the entire
region bounded by the two circles.
- This is a painfully slow notebook. We shold benchmark it to see if the
calculations are the slowest part, or if generating the plots are the slowest
part. 
- It would be nice if we could pre-compute and render frames of a manipulate (so
that it is faster). Not sure if this can be down with the resources available
(my laptop). 

# TODO (proofs):
- Prove the conjectures above.

---
# References:
Cusps in heavy billiards. Boris Hasselblatt, Ki Yeun Kim, and Mark Levi.
Nonlinearity 37 (2024) 025006 (21pp),
[https://doi.org/10.1088/1361-6544/ad1496](https://doi.org/10.1088/1361-6544/ad1496)
[iop](https://iopscience.iop.org/article/10.1088/1361-6544/ad1496)
[pdf](../references/)



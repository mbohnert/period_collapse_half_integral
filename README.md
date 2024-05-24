# Quasi-period collapse in half-integral polygons

A database of half-integral polygons with quasi-period collapse. We present data for pseudo-integral half-integral polygons with at most 6 interior lattice points, for pseudo-integral polygons with denominator at most 17 and 1 interior lattice points, and for pseudo-integral triangles with denominator at most 1000 and 1 interior lattice point.

See [arXiv:2405.13404](https://arxiv.org/abs/2405.13404) for more information about the data provided.

## Data Description
The text files "PIP_dual_Fano_polygons.txt" and "PIP_dual_Fano_triangles.txt" contain data with the following structure. We have one example of a polygon P per line in the form
[denominator of P, vertices of the dual polygon P*, vertices of the lattice polygon denom(P)*P, number of boundary lattice points of P].

The text file "PIP_up_to_6_interior_lattice_points.txt" contains data with the following structure. We have one example of a polygon P per line in the form 
[[number of interior lattice points of P, number of boundary lattice points of P, denominator of P], number of lattice points of denom(P)*P, vertices of denom(P)*P].

## References
The data for pseudo-integral half-integral polygons with at most 6 interior lattice points ware generated from data of lattice polygons with at most 78 lattice points using an algorithm of R. J. Koelman published in: R. J. Koelman, The number of moduli of families of curves on toric surfaces, [PhD Thesis](https://repository.ubn.ru.nl/handle/2066/113957), University of Nijmegen (1991).

The data for pseudo-integral polygons with denominator at most 17 and 1 interior lattice points were generated using data from the [Graded Ring Database](http://www.grdb.co.uk/forms/toricldp) published in: Alexander M. Kasprzyk, Maximilian Kreuzer, Benjamin Nill, "On the combinatorial classification of toric log del Pezzo surfaces", LMS Journal of Computation and Mathematics 13, 2010, 33-46.

The data for pseudo-integral triangles with denominator at most 1000 and 1 interior lattice points were generated using data from [https://github.com/abaeuerle/fano-simplices](https://github.com/abaeuerle/fano-simplices) with background information in: Andreas Bäuerle, "Sharp volume and multiplicity bounds for Fano simplices." [arXiv:2308.12719](https://arxiv.org/abs/2308.12719).


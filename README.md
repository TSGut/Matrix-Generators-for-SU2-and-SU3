# Matrix-Generators-for-SU2-and-SU3

Computes the generators for a given representation of SU2 and SU3 as a list of matrices.

`MatrixRepSU2` returns a specific matrix representation of the group SU(2) with dimension as given via non-optional argument. The method returns a [`List`] of three matrices.

`MatrixRepSU3` returns a specific matrix representation of the group SU(3) with [highest weight] as given via non-optional argument, e.g. for `{1,0}` it will return the [Gell-Mann matrices]. The method returns a [`List`] of eight matrices.

These two Wolfram Mathematica notebooks are a part of [BProbeM], an open source Mathematica package to scan matrix geometries, forked from the original [BProbe]. The code for these two notebooks is subject to GNU license v3, see the original variants [here]. 

The notebooks can in principle be added to Mathematica as part of the BProbeM package if desired but I believe they can perhaps be useful for other purposes and presenting them separate from the BProbeM package can help people who are looking for this find them more easily.

For the purposes of citing, please see the full BProbeM package.

[`List`]: https://reference.wolfram.com/language/ref/List.html
[highest weight]: https://en.wikipedia.org/wiki/Weight_%28representation_theory%29
[Gell-Mann matrices]: https://en.wikipedia.org/wiki/Gell-Mann_matrices
[BProbe]: https://github.com/lschneiderbauer/BProbe
[BProbeM]: https://github.com/TSGut/BProbeM/
[here]: https://github.com/lschneiderbauer/BProbe

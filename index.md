# Google Summer of Code 2020 - Final Report

## Integration of Kenzo program with SimplicialSets

# Overview

[This project](https://summerofcode.withgoogle.com/projects/#4580455350796288) consisted in improving the interface between the [Kenzo Program](https://www-fourier.ujf-grenoble.fr/~sergerar/Kenzo/) and [SageMath](sagemath.org), whose initial version was worked in ticket [\# 27880](https://trac.sagemath.org/ticket/27880). That ticket makes it possible to communicate both computer algebra programs and enhances the SageMath system with new capabilities in algebraic topology, such as the computation of homotopy groups and some kind of spectral sequences, dealing in particular with simplicial objects of infinite nature.

# Trac Ticket 

Bearing in mind the SageMath development process by mean of an issue tracking system called Trac https://trac.sagemath.org, we have created a ''ticket''. This is the name given for an item on the server, where anyone can post on the trac server if a bug is found in SageMath, if new code is ready to be submitted or you want to review new code already written but not yet included in SageMath or if there are corrections for the documentation. Anyone may search or browse the tickets and for a list of recent changes, [Sage trac timeline](https://trac.sagemath.org/timeline) must be visited.

## [#29879 Linking Kenzo simplicial sets to SageMath ones](https://trac.sagemath.org/ticket/29879)

This is the list of commits:

|Commit message (Expand) |	Author |	Age |	Files |	Lines |
|------------------------|----------|----------|----------|----------|
| [Descriptions deleted in lines # optional - kenzo](https://git.sagemath.org/sage.git/commit/?h=015364eab2ace9139eff34605a8a84c6a3171c1b)  |	gh-jcuevas-rozo  |	2020-08-23  |	4 |	-23/+23 |
| [doctests depending on Kenzo marked as optional](https://git.sagemath.org/sage.git/commit/?h=015364eab2ace9139eff34605a8a84c6a3171c1b&id=721a797ff5659dc3112fc347ab296b046cd0adcf)	  | gh-jcuevas-rozo  |	2020-08-11	| 7	| -111/+156 |
| [Documentation added about '_kenzo_repr' attribute](https://git.sagemath.org/sage.git/commit/?h=015364eab2ace9139eff34605a8a84c6a3171c1b&id=7bcb20b7466ed959c1805a49271ea526570bab47)  |	gh-jcuevas-rozo  |	2020-08-03	| 6 |	-40/+795  |
| [classes KenzoAbstractSimplex and KenzoCRPRSimplex added](https://git.sagemath.org/sage.git/commit/?h=015364eab2ace9139eff34605a8a84c6a3171c1b&id=6690673c997dcab6bd585e2c0638feb91cc3cdac)	| gh-jcuevas-rozo	| 2020-07-28 | 3 | -222/+339 |
| [_kenzo_repr attribute added to ProductOfSimplicialSets, WedgeOfSimplicialSets and SmashProductOfSimplicialSets](https://git.sagemath.org/sage.git/commit/?h=015364eab2ace9139eff34605a8a84c6a3171c1b&id=f3d526a3df27763165ef92f14af58fe80bea8c4c) |	gh-jcuevas-rozo |	2020-07-22 |	1 |	-0/+29 |
| [Updated](https://git.sagemath.org/sage.git/commit/?h=015364eab2ace9139eff34605a8a84c6a3171c1b&id=bb822a35db0860c984b8715574bf06697f4c522b)	| gh-jcuevas-rozo |	2020-07-09 |	2 |	-4/+1 |
| [_kenzo_repr added to operations of ChainComplexMorphisms](https://git.sagemath.org/sage.git/commit/?h=015364eab2ace9139eff34605a8a84c6a3171c1b&id=4fbe3f640d5596d48d778034bcc73cc2b8c6dce5) |	gh-jcuevas-rozo |	2020-07-09 |	1 |	-18/+12 |
| [class KenzoCombination created; classes KenzoChainComplex and KenzoChainComplexMorphism callable](https://git.sagemath.org/sage.git/commit/?h=015364eab2ace9139eff34605a8a84c6a3171c1b&id=38ee08ef8a2ff6e71024a2a1ee747ea51a2f2788) |	gh-jcuevas-rozo |	2020-07-09 |	1 |	-23/+528 |
| [_kenzo_repr for compositions of ChainComplexMorphisms added](https://git.sagemath.org/sage.git/commit/?h=015364eab2ace9139eff34605a8a84c6a3171c1b&id=6ed56df11184ba98fd1fbe7180509286f1abfe20)	| gh-jcuevas-rozo |	2020-07-03 |	2 |	-64/+158 |
| [_kenzo_repr attribute added to ChainComplex and ChainComplexMorphism](https://git.sagemath.org/sage.git/commit/?h=015364eab2ace9139eff34605a8a84c6a3171c1b&id=366d23a778510bd877e8c7fa792716f45d473a31) |	gh-jcuevas-rozo |	2020-07-02 |	3 |	-7/+32 |
| [Modifying _kenzo_repr attribute (not optional)](https://git.sagemath.org/sage.git/commit/?h=015364eab2ace9139eff34605a8a84c6a3171c1b&id=d6233314a134c8e8f28703ca4007296c08913422) |	gh-jcuevas-rozo |	2020-06-26 |	3 |	-50/+34 |
| [Parameter kenzo_repr added to special simplicial sets](https://git.sagemath.org/sage.git/commit/?h=015364eab2ace9139eff34605a8a84c6a3171c1b&id=2fccead2569e311889ba257a1d2e0f8ccc110557) |	gh-jcuevas-rozo |	2020-06-24 |	4	| -17/+46 |
| [KAbstractSimplex function changed](https://git.sagemath.org/sage.git/commit/?h=015364eab2ace9139eff34605a8a84c6a3171c1b&id=cc3d7a8ffc91f6ac8acb1a6294fc2cf664dff35e) |	gh-jcuevas-rozo	| 2020-06-21 |	1 |	-1/+2 |
| [Optional parameter kenzo_repr added to AbstractSimplex_class.__init__ and SimplicialSet_finite.__init__](https://git.sagemath.org/sage.git/commit/?h=015364eab2ace9139eff34605a8a84c6a3171c1b&id=e6642779d299c3eb5a96ffd64df0993e555190ce) |	gh-jcuevas-rozo |	2020-06-18 |	2 |	-16/+33 |
| [Minor improvements to kenzo.py](https://git.sagemath.org/sage.git/commit/?h=015364eab2ace9139eff34605a8a84c6a3171c1b&id=ac1cc9c2770276c6b08cfaa795af1585c04cfee6) |	jcuevas-rozo |	2020-06-16 |	1	 | -5/+3 |

## Files modified

### [kenzo.py](https://github.com/sagemath/sage/blob/develop/src/sage/interfaces/kenzo.py)

* 

### [chain_complex.py](https://github.com/sagemath/sage/blob/develop/src/sage/homology/chain_complex.py)

* 

### [chain_complex_morphism.py](https://github.com/sagemath/sage/blob/develop/src/sage/homology/chain_complex_morphism.py)

*

### [simplicial_set.py](https://github.com/sagemath/sage/blob/develop/src/sage/homology/simplicial_set.py)

*

### [simplicial_set_constructions.py](https://github.com/sagemath/sage/blob/develop/src/sage/homology/simplicial_set_constructions.py)

*

### [simplicial_set_examples.py](https://github.com/sagemath/sage/blob/develop/src/sage/homology/simplicial_set_examples.py)

*

### [simplicial_set_morphism.py](https://github.com/sagemath/sage/blob/develop/src/sage/homology/simplicial_set_morphism.py)

*

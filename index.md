# Overview

[This project](https://summerofcode.withgoogle.com/projects/#4580455350796288) consisted in improving the interface between the [Kenzo Program](https://www-fourier.ujf-grenoble.fr/~sergerar/Kenzo/) and [SageMath](sagemath.org), whose initial version was worked in ticket [\# 27880](https://trac.sagemath.org/ticket/27880). That ticket makes it possible to communicate both computer algebra programs and enhances the SageMath system with new capabilities in algebraic topology, such as the computation of homotopy groups and some kind of spectral sequences, dealing in particular with simplicial objects of infinite nature.

# Trac Ticket 

Bearing in mind the SageMath development process by mean of an issue tracking system called Trac https://trac.sagemath.org, we have created a ''ticket''. This is the name given for an item on the server, where anyone can post on the trac server if a bug is found in SageMath, if new code is ready to be submitted or you want to review new code already written but not yet included in SageMath or if there are corrections for the documentation. Anyone may search or browse the tickets and for a list of recent changes, [Sage trac timeline](https://trac.sagemath.org/timeline) must be visited.

## [#29879 Linking Kenzo simplicial sets to SageMath ones](https://trac.sagemath.org/ticket/29879)

This is the list of commits associated to the work done in the project:

| Commit message |	Author |	Age |	Files |	Lines |
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

## Modified files

In the files we were modifying along the development of the project, the next three lines were added to the respective preambles:
```
from sage.interfaces import kenzo
from sage.features.kenzo import Kenzo
kenzo_is_present = Kenzo().is_present()
```
Above lines allow us to know if the Kenzo system is installed and they provide a condition to the Kenzo representations of the Sage objects. The following items show some descriptions of the added functions and changes made on the Kenzo files and SageMath files: 

### [kenzo.py](https://github.com/sagemath/sage/blob/develop/src/sage/interfaces/kenzo.py)

* 

### [sage-interface.lisp](https://github.com/miguelmarco/kenzo/blob/testing/src/sage-interface.lisp)

This is a file where the Kenzo functions are implemented in order to be imported in the file `kenzo.py`.

*  The function `KDFFR` was added to provide the slot _:intr-dffr_ of the KenzoSimplicialSet in SageMath obtained by applying the function `KChainComplex` (in `kenzo.py`) to a ChainComplex in Sage.

* The function `KINTR` was added to provide the slot _:intr_ of the KenzoChainComplexMorphism in SageMath obtained by applying the function `KMorphismChainComplex` (in `kenzo.py`) to a ChainComplexMorphism in Sage. In a similar way, the function `KSINTR` was added to provide the slot _:sintr_ of the KenzoSimplicialMorphism in SageMath obtained by applying the function `KSimplicialSetMorphism` (in `kenzo.py`) to a SimplicialSetMorphism in Sage.

* The function `KCHAINCOMPLEXMORPHISM-AUX` was added to construct a chain complex morphism in Kenzo from the information given by the dictionary of matrices defining a ChainComplexMorphism in Sage. In a similar way, the function `KSIMPLICIALSETMORPHISM-AUX` was added to construct a simplicial set morphism in Kenzo from the information given by the dictionary of matrices defining a SimplicialSetMorphism in Sage

* Some wrapper functions were implemented in order to use combinations (type _CMBN_ in Kenzo) in SageMath (`CMBN-AUX`, `DFFR-AUX1`, `EVALUATE-CMBN`) and wrapper functions to deal with abstract simplexes (type _ABSM_ in Kenzo) and abstract simplexes of cartesian products (type _CRPR_ in Kenzo) in SageMath were added (`ABSM-AUX`, `DEGENERATE-P`, `NON-DEGENERATE-P`, `CRPR-ABSM-AUX`, `ABSM1`, `ABSM2`, `KABSTRACTSIMPLEX-AUX`) among other functions.


### [chain_complex.py](https://github.com/sagemath/sage/blob/develop/src/sage/homology/chain_complex.py)

* The \_kenzo\_repr\_ attribute was added to the class ChainComplex_class: when a ChainComplex in Sage has grading group the set of integer numbers and the degree of differential is -1, its Kenzo representation is constructed (these are restrictions given by the Kenzo system).


### [chain_complex_morphism.py](https://github.com/sagemath/sage/blob/develop/src/sage/homology/chain_complex_morphism.py)

* The \_kenzo\_repr\_ attribute was added to the class ChainComplexMorphism: if the source complex and the target complex have \_kenzo\_repr\_ attributes, the Kenzo representation of the morphism is constructed.

* Different operations between ChainComplexMorphisms have Kenzo representations: the opposite of a morphism, sum of morphisms, composition of morphisms, multiplication by an integer number, substraction of morphisms. All of these operations have \_kenzo\_repr\_ attributes whenever the involved morphisms have Kenzo representations.


### [simplicial_set.py](https://github.com/sagemath/sage/blob/develop/src/sage/homology/simplicial_set.py)

* The \_kenzo\_repr\_ attribute was added to the class AbstractSimplex_class. This needed the implementation of the class KenzoAbstractSimplex in `kenzo.py`. Different methods of this class have the respective Kenzo representations: degeneracies, nondegenerate part of an abstract simplex, the product of abstract simplexes (this needed the implementation of the class KenzoCRPRSimplex in `kenzo.py`).

* In the class SimplicialSet_arbitrary, the `join` method is not implemented, but in Kenzo this operation is available. The join of simplicial sets is created as a KenzoSimplicialSet whenever the onvolved simplicial sets have \_kenzo\_repr\_ attributes. In the class SimplicialSet_finite, the \_kenzo\_repr\_ attribute was also added.


### [simplicial_set_constructions.py](https://github.com/sagemath/sage/blob/develop/src/sage/homology/simplicial_set_constructions.py)

* In class `PullbackOfSimplicialSets_finite`, the stored information in attribute `self._translation` is used for "translate" the involved simplexes to their Kenzo equivalent abstract simplexes. Since the product of simplicial sets is implemented in SageMath as a pullback, this translation allows us to associate the \_kenzo\_repr\_ attribute to the class `ProductOfSimplicialSets`.

* In classes `PushoutOfSimplicialSets_finite` and `PushoutOfSimplicialSets`, the \_kenzo\_repr\_ attribute was added bearing in mind that (by now) only pushouts of two morphisms are constructed in Kenzo.

* The \_kenzo\_repr\_ attribute was also added to the classes `SmashProductOfSimplicialSets_finite` and `SmashProductOfSimplicialSets`, where the Kenzo analog is constructed if all the involved factors have their Kenzo representation. The same was made for classes `WedgeOfSimplicialSets` and `WedgeOfSimplicialSets_finite`.

* If a simplicial set has \_kenzo\_repr\_ attribute, its suspension have a Kenzo representation (implemented in classes `SuspensionOfSimplicialSet` and `SuspensionOfSimplicialSet_finite`).

### [simplicial_set_examples.py](https://github.com/sagemath/sage/blob/develop/src/sage/homology/simplicial_set_examples.py)

* In the function `Sphere` was assign the \_kenzo\_repr\_ attribute in order to construct a Kenzo sphere, which is possible when the dimension of the sphere is less than 15 (the maximal dimension allowed in Kenzo system). Also, in `Simplex` function the Kenzo analog (`DELTA` function) was added as the \_kenzo\_repr\_ attribute. In the function `RealProjectiveSpace` the \_kenzo\_repr\_ attribute was assigned allowing the construction of the analog finite or infinite dimensional real projective space in Kenzo.

### [simplicial_set_morphism.py](https://github.com/sagemath/sage/blob/develop/src/sage/homology/simplicial_set_morphism.py)

*

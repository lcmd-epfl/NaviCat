NaviCat: A platform for catalyst discovery
==========================================

![NaviCat logo](./images/navicat_logo.png)

## Contents
* [About](#about-)
* [Packages](#packages-)
* [Databases](#databases-)
* [Documentation](#documentation-)
* [Examples](#examples-)
* [References](#references-)
* [Acknowledgements](#acknowledgements-)

## About [↑](#about)

NaviCat is a platform that collects tools and databases for digital catalyst optimization and discovery developed at the [LCMD](https://www.epfl.ch/labs/lcmd/) in EPFL. This hub is currently under construction, hence some of the tools listed may be in development or not currently public yet.

## Packages [↑](#packages)

* [NaviCatGA](https://github.com/lcmd-epfl/NaviCatGA), a Genetic Algorithm for catalyst optimization.
* [volcanic](https://github.com/lcmd-epfl/volcanic), an automated tool for volcano plot and activity map building.
* [mikimo](https://github.com/lcmd-epfl/mikimo), an automated tool for microkinetic volcano plot building.
* [EPSim](https://github.com/lcmd-epfl/EPSim), a tool to calculate the  distance to Sabatier's ideal catalyst.
* [MORESIM](https://github.com/lcmd-epfl/MORESIM), a module to perform replica exchange simulations.
* [LKR](https://github.com/lcmd-epfl/Local_Kernel_Regression), a step-by-step demonstration of local kernel ridge regression for machine learning applications.
* [b2r2](https://github.com/lcmd-epfl/b2r2-reaction-rep), a reaction-based representation for machine learning applications.
* [Reaction representation of organocatalysts](https://github.com/lcmd-epfl/reaction-representation), a step-by-step demonstration of how to generate reaction representations for the prediction of selectivity in enantioselective organocatalysis. Includes a database of 754 activation energies.

## Databases [↑](#databases)

* [Data mining the C-C cross-coupling genome](https://www.materialscloud.org/discover/ccg#mcloudHeader), a database of C-C cross-coupling transition metal catalysts and their predicted performance for different reactions.
* [OSCAR](https://archive.materialscloud.org/record/2022.106), an extensive repository of chemically and functionally diverse organocatalysts. Contains thousands of organocatalysts with relevant properties, and can be visualized using [Chemiscope](https://chemiscope.org/). 
* [Hydroform-22-TS](https://github.com/lcmd-epfl/b2r2-reaction-rep), a database of 2350 structures of intermediates before and after the alkene insertion transition state in the catalytic cycle of olefin hydroformylation and the corresponding energies.

## Examples [↑](#examples)

Will be added as more tools are added to the project.

## References [↑](#contents)

* R. Laplaza, S. Gallarati, and C. Corminboeuf, “Genetic Optimization of Homogeneous Catalysts”, Chem.- Methods. **2**, e202100107 (2022) [![DOI](https://img.shields.io/badge/DOI-10.1002%2Fcmtd.202100107-blue)](https://doi.org/10.1002/cmtd.202100107)
* P. van Gerwen, A. Fabrizio, M. D. Wodrich, and C. Corminboeuf, "Physics-based representations for machine learning properties of chemical reactions", Mach. Learn.: Sci. Technol. **3**, 045005 (2022) [![DOI](https://img.shields.io/badge/DOI-10.1088/2632--2153/ac8f1a-blue)](https://doi.org/10.1088/2632-2153/ac8f1a)
* R. Fabregat, P. van Gerwen, M. Heberle, F. Eisenbrand, and C. Corminboeuf, "Metric learning for kernel ridge regression: assessment of molecular similarity", Mach. Learn.: Sci. Technol. **3**, 035015 (2022) [![DOI](https://img.shields.io/badge/DOI-10.1088/2632--2153/ac8e4f-blue)](https://doi.org/10.1088/2632-2153/ac8e4f)
* R. Laplaza, S. Das, M. D. Wodrich, and C. Corminboeuf, "Constructing and interpreting volcano plots and activity maps to navigate homogeneous catalyst landscapes", Nat. Protoc. **17**, 2550–2569 (2022) [![DOI](https://img.shields.io/badge/DOI-10.1038%2Fs41596--022--00726--2-blue)](https://doi.org/10.1038/s41596-022-00726-2)
* S. Gallarati, R. Laplaza, and C. Corminboeuf, "Harvesting the fragment-based nature of bifunctional organocatalysts to enhance their activity", Org. Chem. Front. **9**, 4041-4051 (2022) [![DOI](https://img.shields.io/badge/DOI-10.1039/D2QO00550F-blue)](https://doi.org/10.1039/D2QO00550F)
* R. Laplaza, J. G. Sobez, M. D. Wodrich, M. Reiher, and C. Corminboeuf, "The (not so) simple prediction of enantioselectivity – a pipeline for high-fidelity computations", Chem. Sci. **13**, 6858-6864 (2022) [![DOI](https://img.shields.io/badge/DOI-10.1039/D2SC01714H-blue)](https://doi.org/10.1039/D2SC01714H)
* M. D. Wodrich, M. Chang, S. Gallarati, Ł. Woźniak, N. Cramer, and C. Corminboeuf, "Mapping Catalyst–Solvent Interplay in Competing Carboamination/Cyclopropanation Reactions", Chem. Eur. J. **28**, e202200399 (2022) [![DOI](https://img.shields.io/badge/DOI-10.1002/chem.202200399-blue)](https://doi.org/10.1002/chem.202200399)
* S. Das, R. Laplaza, J. T. Blaskovits, C. Corminboeuf, "Mapping Active Site Geometry to Activity in Immobilized Frustrated Lewis Pair Catalysts", Angew. Chem. Int. Ed. **61**, e202202727 (2022) [![DOI](https://img.shields.io/badge/DOI-10.1002/anie.202202727-blue)](https://doi.org/10.1002/anie.202202727)
* S. Gallarati, R. Fabregat, R. Laplaza, S. Bhattacharjee, M. D. Wodrich, and C. Corminboeuf, "Reaction-based machine learning representations for predicting the enantioselectivity of organocatalysts", Chem. Sci. **12**, 6879-6889 (2021) [![DOI](https://img.shields.io/badge/DOI-10.1039/D1SC00482DD-blue)](https://doi.org/10.1039/D1SC00482DD)


## Acknowledgements [↑](#contents)

The NaviCat project is funded by [NCCR Catalysis](https://www.nccr-catalysis.ch/)  of the [Swiss National Science Foundation](https://www.snf.ch/en) and by the [European Research Council](https://erc.europa.eu/) (ERC, Grant Agreement No. 817977) within the framework of European Union's H2020.

![ackw logo](./images/ackw.png)

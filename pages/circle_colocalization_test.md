## CIRCOAST: A Statistical Hypothesis Test for Cellular Colocalization with Network Structures

<br>
<img src="https://github.com/bacorliss/bacorliss.github.io/blob/e29c876e1a491f92bb87f28f836e5b11f376232c/images/project_circoast.jpeg?raw=TRUE"/>
<br><br>
**Project description:** During my graduate research, I developed a statistical hypothesis test to probe for changes in spatial interactions between two cell populations. This analysis is done on a set of biomdeical images where both cell populations are labeled. Users quantify the count of both cell types within each image, along with the number of cells that overlap between the two groups. When the user also inputs the average cell size for both populations, Monte Carlo simulations are used to determine the average fraction of cells overlapping by random chance.
<br><br>

**Github Repository:** <br>
[https://github.com/uva-peirce-cottler-lab/ARCAS](https://github.com/uva-peirce-cottler-lab/ARCAS)
<br><br>


------

**Publication:** <br>
B. A. Corliss, H. C. Ray, J. T. Patrie, J. Mansour, S. Kesting, J. H. Park, G. Rohde, P. A. Yates, K. A. Janes, S. M. Peirce, CIRCOAST: a statistical hypothesis test for cellular colocalization with network structures. Bioinformatics. 35, 506–514 (2019). Doi: [https://doi.org/10.1093/bioinformatics/bty638](https://doi.org/10.1093/bioinformatics/bty638).
<br>

**Abstract:** 
<br>
**Motivation**
Colocalization of structures in biomedical images can lead to insights into biological behaviors. One class of colocalization problems is examining an annular structure (disk-shaped such as a cell, vesicle or molecule) interacting with a network structure (vascular, neuronal, cytoskeletal, organellar). Examining colocalization events across conditions is often complicated by changes in density of both structure types, confounding traditional statistical approaches since colocalization cannot be normalized to the density of both structure types simultaneously. We have developed a technique to measure colocalization independent of structure density and applied it to characterizing intercellular colocation with blood vessel networks. This technique could be used to analyze colocalization of any annular structure with an arbitrarily shaped network structure.
<br>
**Results**
We present the circular colocalization affinity with network structures test (CIRCOAST), a novel statistical hypothesis test to probe for enriched network colocalization in 2D z-projected multichannel images by using agent-based Monte Carlo modeling and image processing to generate the pseudo-null distribution of random cell placement unique to each image. This hypothesis test was validated by confirming that adipose-derived stem cells (ASCs) exhibit enriched colocalization with endothelial cells forming arborized networks in culture and then applied to show that locally delivered ASCs have enriched colocalization with murine retinal microvasculature in a model of diabetic retinopathy. We demonstrate that the CIRCOAST test provides superior power and type I error rates in characterizing intercellular colocalization compared to generic approaches that are confounded by changes in cell or vessel density.

-------
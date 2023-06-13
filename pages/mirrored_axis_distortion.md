## This can be your internal website page / project page

**Project description:** I developed a new transform and visualization for fold change data for use in bioinformatics research, and demonstrate it's utility with real bioinformatics datasets. This research yielded a publication and code repository implemented in R.

**Reference Publication:** <br>
B. A. Corliss, Y. Wang, F. P. Driscoll, H. Shakeri, P. E. Bourne, MAD-FC: A Fold Change Visualization with Readability, Proportionality, and Symmetry (2023), [doi:10.48550/arXiv.2303.10829](doi:10.48550/arXiv.2303.10829).
<br><br>
**Github Repository:** <br>
[https://github.com/bacorliss/mirrored_axis_distortion](https://github.com/bacorliss/mirrored_axis_distortion)


**Abstract:** We propose a fold change visualization that demonstrates a combination of properties from log and linear plots of fold change. A useful fold change visualization can exhibit: (1) readability, where fold change values are recoverable from datapoint position; (2) proportionality, where fold change values of the same direction are proportionally distant from the point of no change; (3) symmetry, where positive and negative fold changes are equidistant to the point of no change; and (4) high dynamic range, where datapoint values are discernable across orders of magnitude. A linear visualization has readability and partial proportionality but lacks high dynamic range and symmetry (because negative direction fold changes are bound between [0, 1] while positive are between [1, ∞]). Log plots of fold change have partial readability, high dynamic range, and symmetry, but lack proportionality because of the log transform. We outline a new transform and visualization, named mirrored axis distortion of fold change (MAD-FC), that extends a linear visualization of fold change data to exhibit readability, proportionality, and symmetry (but still has the limited dynamic range of linear plots). We illustrate the use of MAD-FC with biomedical data using various fold change charts. We argue that MAD-FC plots may be a more useful visualization than log or linear plots for applications that require a limited dynamic range (approximately ±2 orders of magnitude or ±8 units in log2 space).

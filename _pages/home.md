---
permalink: /
title: "Welcome"

---
Hello! Welcome to my personal page. My name is Pedro, and I`m currently (as of time of writing) \\
a second year PhD student in Materials Science and Engineering, at the National Institute for Materials Science (NIMS) / University of Tsukuba in Tsukuba, Japan.

My current work involves in optimizing/searching magnetocaloric materials for possible use in solid-state hydrogen liquefaction systems.
To achieve this, I mostly work with using data-driven models (constructed on experimental data), together with "traditional" methods (ie. chemical substituion)
to optimize and search for such materials. I use a lot of python to automatize my analysis (to quickly deal with characterization data, mostly magnetization). 
Now I am currently focusing in solving one the bottlenecks (that I actually encountered) in data driven candidate search: Automatic identification of phases in XRD patterns.

To help in solving this issue, I recently published the open source package XERUS (Xray Estimation Using Similarity and Refinement).
XERUS is a tool created after roughly one year and half of work (working on and off) to help me accelerate my research workflow from material prediction & screening and synthesis to property evaluation. It relies mostly on similarity calculation plus structure refinement, so it does not require any model pre-training, so it kinda can be used on-the-fly to obtain quick results just after an experiment finished.

I have recently put a paper on [arXiv](https://arxiv.org/abs/2112.04773), and it is freely available at my [GitHub](https://www.github.com/pedrobcst/Xerus). You can check few [Examples](https://github.com/pedrobcst/Xerus/blob/master/Examples/Examples.ipynb) on few of our own data. We also have a [Benchmark](https://github.com/pedrobcst/Xerus/blob/master/Examples/Benchmark_AutoXRD.ipynb) of XERUS and the most recent (up to my knowledge) CNN-based deep learning approach for **multiphase** classification of XRD.

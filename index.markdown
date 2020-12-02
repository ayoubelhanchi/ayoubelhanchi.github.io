---
layout: page
---
<img style="float: right;
    margin-top: 25px;
    margin-bottom: 35px;
    max-width: 30%;
    border: 6px solid #ddd;
    border-radius: 50%;
    box-sizing: border-box;"
    src="files/picture_1.jpg">

I am a master's student in Mathematics and Statistics at
[McGill University](https://www.mcgill.ca/),
supervised by [David Stephens](http://www.math.mcgill.ca/dstephens/).
I completed my bachelor's degree in
[Honours Mathematics and Computer Science](https://www.mcgill.ca/mathstat/undergraduate/programs/b-sc/joint-honours-mathematics-and-computer-science-b-sc).


My research interests lie at the intersection of theory and algorithms
for machine learning and statistics. My recent focus
has been on developing new variance reduction methods to
accelerate the training of large models.
In particular, I have been exploring the use of online and reinforcement
learning ideas to design better optimization and sampling algorithms.


More broadly, I am interested in developing the computational  
and statistical tools needed to build systems that can make optimal  
decisions under uncertainty.

[Resume](files/resume.pdf) / [Google Scholar](https://scholar.google.com/citations?user=5ZzcGmgAAAAJ&hl=en&oi=ao)


### Papers ###
**Adaptive Importance Sampling for Finite-Sum
Optimization and Sampling with Decreasing Step-Sizes.**  
Ayoub El Hanchi, David A. Stephens  
*(To appear in) Advances in Neural Information Processing Systems, 2020*  
<a href="files/paper_1.pdf">paper</a> | [slides](presentation_1.pdf) | [poster](poster_1.pdf)

### Preprints ###
**A Lyapunov Analysis of Loopless SARAH.**  
Ayoub El Hanchi  
<a href="files/paper_2.pdf">paper</a>

### Software ###
**TorchVr (in progress)**  
A PyTorch library providing PyTorch modules and samplers that produce efficient gradient estimators to accelerate training of large scale models.  
All samplers are written in C++ using an efficient tree implementation for increased performance.
The C++ code is then exposed to python
using [pybind11](https://github.com/pybind/pybind11).  
<a href="files/code_1.zip">source

### Previous Reports  ###
+ *Langevin Diffusion as Gradient Flow in Wasserstein Space.*  
<a href="files/report_4.pdf">report</a>
+ *Scaling up MCMC for Bayesian inference using adaptive data subsampling.*  
<a href="files/report_3.pdf">report</a> \|
<a href="files/presentation_4.pdf">slides</a>
+ *Statistical learning under a non-iid data generating process.*  
<a href="files/report_2.pdf">report</a>

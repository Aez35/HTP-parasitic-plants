The correlation between plant genotypes and phenotypes is often a tedious task that requires destructive, time-consuming methods. Traditional methods of studying plant phenomics presents a bottle-neck in agricultural research that can be overcome through the implementation of high-throughput phenotyping (HTP). HTP allows the input of many samples for rapid analysis, and is capable of measuring multiple characteristics of subjects in a non-destructive manner to determine key features that distinguishes phenotypes of various genotypes. 

This project focuses on implementing high-throughput phenotyping methods to study the parasitic plant species, _cuscuta Campestris_, and various host species. The goal of the project is to construct 3-D models of the _c. Campestris_ using **structure from motion** and **multi-view steroe** techniques. These models can be used to determine phenotypic expression of the genotypes and be used to further parasitic plant research in a high-throughput and non-destructive manner.

This pipeline consists of four steps:

**1)** Image acquisition
**2)** Scale invariant feature detection
**3)** Reconstruction of dense point clouds using **MVE** (SFM and MVS)
**4)** Parameter Estimation

System requirements to compile and run MVE or UVME are:

- libjpeg (for MVE, http://www.ijg.org/)
- libpng (for MVE, http://www.libpng.org/pub/png/libpng.html)
- libtiff (for MVE, http://www.libtiff.org/)
- OpenGL (for libogl in MVE and UMVE)
- Qt 5 (for UMVE, http://qt.nokia.com)


1) Images were acquired using a Sony alpha7 ii camera with the following parameters:

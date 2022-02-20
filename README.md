# Chunks
-------

An open-source multi-scale geological logging from drill-core multivariate data
This is the code repository for the publication submitted to Geoscientific Model Development (GMD). 
-------

Title
-------
Automated multi-scale and multivariate geological logging from drill-core hyperspectral data

Authors
-------
Roberto De La Rosa, Raimon Tolosana-Delgado, Moritz Kirsch and Richard Gloaguen

Abstract
-------
Hyperspectral drill-core scanning adds value to exploration campaigns by providing continuous, high-resolution mineralogical data over the length of entire boreholes. However, multivariate mineralogical data has to be transformed into lithological domains such that it is compatible with interpolation techniques and be usable for geomodelling. Manual interpretation of multivariate drill-core data is a challenging, time-consuming and subjective task, and automated or semi-automated approaches are needed. However, naive machine learning techniques that ignore the distinct spatial structure and multi-scale nature of geological systems tend to produce geologically unreasonable results. Automated geological logging and multi-scale hierarchical domaining of drill-cores has been previously addressed in several studies by means of scalograms from a wavelet transform and tessellation, albeit exploiting only univariate information. 
The methodology involves the  extraction of the local first principal component at a neighborhood of each observation, and the segmentation of the resulting series of scores with a continuous wavelet transform for boundary detection. In this way, the correlation pattern between the variables is incorporated into the segmentation. The scalogram accurately locates the geological boundaries at depth and yields hierarchical geological domains with mineralogical composition characteristics. The performance  of this approach is demonstrated on a synthetic as well as a real multivariate dataset. The real dataset consists of mineral abundances derived from drill-core hyperspectral imaging data acquired in Elvira, a shale-hosted volcanogenic massive sulphide deposit located in the Iberian Pyrite Belt, where 7000 m of drill-core were acquired along 80 boreholes. The extracted domains are sensible from a geological point of view and also spatially coherent across the boreholes in cross-sections. The results at relevant  scales were qualitatively validated by comparing against the lithological log. This method is fast, appropriate for multivariate geological data along boreholes and provides a choice of scales for hierarchical geological domains along boreholes with mineralogical composition characteristics that can be modeled in 3D. Our approach provides an automatic way to transform hyperspectral image-derived mineral maps into vertically coherent geological units that are appropriate inputs for 3D geological modelling workflows. Moreover, the method  improves the boundary detection and geological domaining by making use of multivariate information.

Keywords
-------
Hyperspectral data, Drill-cores, Mineral quantification, Geological domains, Borehole segmentation, Lithological classification, 3D modelling.


-------

![workflow image](docs/fig02.png)

* General workflow for multi-scale, multivariate borehole segmentation from hyperspectral drill-core data.*

-------


Contributing to  Chunks
-------

Additions and Bug reports  are more than welcomed!
Please feel free to submit pull requests through GitHub or get in touch with me directly if
you have any questions. 

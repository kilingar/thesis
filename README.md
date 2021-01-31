N. G. Kilingar, “Generation and data-driven upscaling of open foam representational volume elements,” Université de Liège, Liège, Belgique, 2021.

Thesis Source Files

Abstract:
In this work, a Representative Volume Element (RVE) generator based on the distance fields of arbitrary shaped inclusion packing is used to obtain morphologies of open-foam materials. When the inclusions are spherical, the tessellations of the resultant packing creates morphologies that are similar to physical foam samples in terms of their face-to-pore ratio, edge-to-face ratio and strut length distribution among others. Functions that combine the distance fields can be used to obtain the tessellations along with the necessary variations in the strut geometry and extract these open-foam morphologies. It is also possible to replace the inclusion packing with a predefined set of inclusions that are directly extracted from CT-scan based images.

The use of discrete level-set functions results in steep discontinuities in the distance function derivatives. A multiple level-set based approach is presented that can appropriately capture the sharp edges of the open-foam struts from the resultant distance fields. Such an approach can circumvent the discontinuities presented by the distance fields which might lead to spurious stress concentrations in a material behavior analysis.

The individual cells are then extracted as inclusion surfaces based on said combinations of the distance functions and their modifications. These surfaces can be joined together to obtain the final geometry of the open-foam morphologies. The physical attributes of the extracted geometries are compared to the experimental data. A statistical comparison is presented outlining the various features. The study is extended to morphologies that have been extracted using CT-scan images.

With the help of mesh optimization tools, surface triangulations can be obtained, merged and developed as finite element (FE) models. The models are ready to use in a multi-scale study to obtain the homogenized material behavior. The upscaling can help assess the practical applications of these models by comparing with experimental data of physical samples. The material behavior of the RVEs are also compared with the experimental observations.

To increase the computational efficiency of the study, a neural network based surrogate is presented that can replace the micro-scale boundary value problem (BVP) in the multi-scale analysis. The neural networks are built with the help of modules that are specifically designed to predict history dependent behavior and are called Recurrent Neural Networks (RNN). The surrogates are trained to take into account the randomness of the loading that complex material undergo during any given material behavior analysis.


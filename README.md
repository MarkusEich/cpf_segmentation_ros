# cpf_segmentation_ros
ROS node for using cpf segmentation for unsupervised segmentation of 3D points. Need cpf_segmentation to run

```
git clone https://github.com/MarkusEich/cpf_segmentation)
```
If you want to cite this work, you can use the bibtex entry below

```
@inproceedings{Pham2016,
abstract = {Modern SLAM systems with a depth sensor are
able to reliably reconstruct dense 3D geometric maps of indoor
scenes. Representing these maps in terms of meaningful entities
is a step towards building semantic maps for autonomous
robots. One approach is to segment the 3D maps into semantic
objects using Conditional Random Fields (CRF), which requires
large 3D ground truth datasets to train the classification
model. Additionally, the CRF inference is often computationally
expensive. In this paper, we present an unsupervised geometricbased
approach for the segmentation of 3D point clouds into
objects and meaningful scene structures. We approximate an
input point cloud by an adjacency graph over surface patches,
whose edges are then classified as being either on or off. We
devise an effective classifier which utilises both global planar
surfaces and local surface convexities for edge classification.
More importantly, we propose a novel global plane extraction
algorithm for robustly discovering the underlying planes in the
scene. Our algorithm is able to enforce the extracted planes
to be mutually orthogonal or parallel which conforms usually
with human-made indoor environments. We reconstruct 654 3D
indoor scenes from NYUv2 sequences to validate the efficiency
and effectiveness of our segmentation method.
},
author = {Pham, Trung T. and Eich, Markus and Reid, Ian and Wyeth, Gordon}
booktitle = {2016 IEEE/RSJ International Conference on Intelligent Robots and Systems, IROS},
month = {October},
pages = {},
publisher = {IEEE},
title = {{Geometrically Consistent Plane Extraction for
Dense Indoor 3D Maps Segmentation}},
year = {2016}
}
```



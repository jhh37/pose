# pOSE: Pseudo Object Space Error for Initialization-Free BA (CVPR 2018)

## Abstract
Bundle adjustment is a nonlinear refinement method for camera poses and
3D structure requiring sufficiently good initialization. In recent
years, it was experimentally observed that useful minima can be reached
even from arbitrary initialization for affine bundle adjustment
problems (and fixed-rank matrix factorization instances in general).
The key success factor lies in the use of the variable projection
(VarPro) method, which is known to have a wide basin of convergence for
such problems. In this paper, we propose the Pseudo Object Space Error
(pOSE), which is an objective with cameras represented as a hybrid
between the affine and projective models. This formulation allows us to
obtain 3D reconstructions that are close to the true projective
reconstructions while retaining a bilinear problem structure suitable
for the VarPro method. Experimental results show that using pOSE has a
high success rate to yield faithful 3D reconstructions from random
initializations, taking one step towards initialization-free structure
from motion.

## Contributors
- Je Hyeong Hong (jhh37@cantab.net)
- Christopher Zach (christopher.m.zach@gmail.com)

## Paper
The main paper file is included in the ''Documents'' folder.
(The corresponding supplementary document will be uploaded soon.)

## Video
URL: https://youtu.be/1Ef441Ki4sI

This video shows iterative visualizations of the bundle adjustment
strategy using pOSE from arbitrary cameras and 3D points. (3 datasets
from Carl Olsson shown here.)
For this strategy to work, sufficiently cleaned 2D point tracks (can
have some outliers) are required as well as camera intrinsics.

## Acknowledgement
- We thank Roberto Cipolla for the travel support.
- The conference travel was supported by Roberto Cipolla, Toshiba
Research Europe and Christ's College.

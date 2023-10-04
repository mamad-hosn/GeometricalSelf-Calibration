# Geometrical Self-Calibration
This is a study of a multivariate optimization problem that aims to find the optimal values of six geometrical parameters of a CBCT system using gradient descent. The cost function is based on the mutual information.
#
Different from the phantom-base methods, no phantom study is required before the imaging tasks in self-calibration methods.
The geometric parameters are obtained from the imaging objects themselves. Due to the omission of phantom scans, a selfcalibration method has some advantages especially in mechanically unstable systems, high-resolution CT, frequently adjusted
systems, and many others. However, accurate acquisition of all the geometric parameters with self-calibration method remains
a challenge, because no geometric information of imaging object is available. Obviously, if there is a dynamic and variable
geometric structure in the system, we need to re-image the phantom to calibrate the system. But in projection base methods, we
use the correlation created between the images due to the geometry of the system and obtain the geometric parameters. For this
purpose, we have a prior knowledge about the object and using their DRRs1
, we generate the result with different geometries,
based on comparing it with the captured images and measuring their similarity, in this way, we extract the accurate geometry. In
our proposed method, it is no longer necessary to have basic information about the object, and we extract the geometry of the
system only by having projections.


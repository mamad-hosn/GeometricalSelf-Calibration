# Geometrical Self-Calibration
This is an abstract of a conference paper that investigates a multivariate optimization problem for a CBCT system. The paper proposes a gradient descent method to optimize five geometrical parameters that affect the image quality and radiation dose. The paper uses mutual information as the cost function to measure the similarity between the reconstructed and original images. The paper evaluates the performance of the proposed method on simulated and real data.
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
# the diagram of optimization
![201](https://github.com/mamad-hosn/GeometricalSelf-Calibration/assets/90955072/25f923a8-4a8f-48af-b3ab-67966bf5c3f3)
![202](https://github.com/mamad-hosn/GeometricalSelf-Calibration/assets/90955072/91ef7daa-b9f4-4cb2-897d-8e070333f64f)

# conclusion
![303](https://github.com/mamad-hosn/GeometricalSelf-Calibration/assets/90955072/fee822d8-266a-4ee8-bf5f-5c57a8c6ac88)


can we fix the optimization parameter during the ICP process. First Rotation, then translation
# Symmetric ICP
## point-to-point
slow convergence rate  
### point to point good at handling translation, bad at rotation
## point-to-plane
### point to plane good at handling rotation, bad at translation
fast convergence rate, but narrower convergence basin.  
the residual at optimal alignment is zero only when the surface is locally flat, if the correspondences are not perfect (which
is necessarily the case if point sets {pi } and {qi } differ in their
sampling of the surface, as with 3D scans). This is important because the zero-set of the objective function defines what transformations are łfree,ž in the sense that the surface is allowed to slide
along itself to permit geometric features elsewhere to lock down
the transformation.  
## symmetric_icp: 
We therefore seek to develop a new objective function whose
zero-set allows a greater class of surfaces to łslide alongž themselves at zero penalty. Thinking within the framework of Expectation Maximization, this makes the method as robust as possible to
mis-estimation of point correspondences in the Expectation step.

# Registration of point cloud data from a geometric optimization perspective
Pottmann and Hofer showed that when the data and
the model are close, the point-to-plane distance is a good
approximation to the distance between a data point and the
surface represented by the model PCD. On the other hand,
when the model and the data are far apart, the point-to-point
distance is a better choice 




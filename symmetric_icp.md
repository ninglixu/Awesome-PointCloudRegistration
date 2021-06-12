#point-to-point : slow convergence rate  
#point-to-plane: fast convergence rate, but narrower convergence basin.  
the residual at optimal alignment is zero only when the surface is locally flat, if the correspondences are not perfect (which
is necessarily the case if point sets {pi } and {qi } differ in their
sampling of the surface, as with 3D scans). This is important because the zero-set of the objective function defines what transformations are łfree,ž in the sense that the surface is allowed to slide
along itself to permit geometric features elsewhere to lock down
the transformation.  
#symmetric_icp: We therefore seek to develop a new objective function whose
zero-set allows a greater class of surfaces to łslide alongž themselves at zero penalty. Thinking within the framework of Expectation Maximization, this makes the method as robust as possible to
mis-estimation of point correspondences in the Expectation step.

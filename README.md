# Upenn CIS580 Machine Perception, Project2

Given consecutive images and their feature data, Milestone 3 achieve the Structure from Motion Pipeline. It involves epipolar RANSAC, Essential Matrix decomposition, linear/nonlinear Triangulation, PnP RANSAC, linear/nonlinear PnP and Bundle Adjustment with Jacobian.

The result and visualization suggest the reprojection error is gradually minimized in the pipeline. Also, I replace built-in lsqnonlin by gradient descent optimization in Milestone 3.v2 to improve accuracy(0.75pixel to 0.5pixel) and runtime(150s to 60s) greatly.

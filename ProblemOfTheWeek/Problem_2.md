## Problem of the week

1. Design a function named CreateBlobs(nos_centers=4, num_points=100, split="uniform", dist="uniform", width_horizontal, width_vertical)
  - nos_centers: number of centers to create blobs; default has to be 3
  - num_points: total number of points to generate
  - split: it is string which can have the following values. uniform, random. If uniform we the function has to divide the num_points equally
to all centers. if random split the num_points/center in a random fashion
  - dist: type of distribution to generate, it can take the following strings gaussian, landau, uniform
     * width_horizantal = horizontal spread in the distribution of the points
     * width_vertical = vertical spread in the distribution of the points

2. The function has to return a bunch of points (x,y) which should be in
the form of a numpy array or pandas. these can be plotted as a
scattering plot to visualise the generated points

3. As an example please try to look into Joachim's notebook for the
library which creates blobs.

4. Please make sure you follow the same naming as we are focusing on
developing a class out of these functions.

5. Please ask any questions whenever you have an issue

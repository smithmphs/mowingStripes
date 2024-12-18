#  <p align=center>Statistical Mechanics of Mowing Stripes on Golf Course Greens</p>


Consider the greensmower below.

<p align=center>
  <img src=striping.png>
</p>

See the mowing stripes his mower is creating in the background? Folklore says these stripes are due to differences in how the grass is bent. The folklore is probably true but nobody has proven it, much less examined the underlying statistics. So our aim here to do just that by collecting high-resolution pictures of mowing stripes and looking for correlations in the trajectories of the individual grass blades contained therein.  You can view our first attempt [here](experimentOne/README.md).  The next time you play a round, consider taking some pictures and sending them our way.  Together we will figure this out.  Thanks.

  * [First Experiment](experimentOne/README.md) : our first attempt, a beautiful summer morning on a green freshly mowed using a riding triplex.
  * [Second](experimentTwo/README.md) : a sunny afternoon, on a green mowed laterally (with respect to the approach) several hours before.  Annotated cardboard templates were included in the photographs for the first time to ease post-processing.
  * [Sanity Check](experimentThree/README.md) : if the same area of turf is photographed repeatedly but at different angles, how does the dominant angle change?
  * [Another Sanity Check](experimentFour/README.md):  does illumination affect the called dominant angle?
  * [Still Another Check](experimentFive/README.md): when the grass is mussed up, how does this affect the angle and coherency?

For analysis, we have been using [orientationj](https://bigwww.epfl.ch/demo/orientation/) and [orientationpy](https://epfl-center-for-imaging.gitlab.io/orientationpy/introduction.html) thus far.  The latter outputs some especially artful analysis as shown below using a small snippet of bent grass.  This also serves to illustrate how the software calls the angles.

 <p align=center>
   <img src=sigma9.jpg>
 </p>


## BMB

- think about distances more; try implementing Mahalanobis dists for probes?
- difference between "closest to Fréchet mean" and "most central" ?
- efficient algorithms?
- think about Juul et al's sampling algorithms: are they principled in some way we don't understand?
- efficient algorithms?

## AG

- is there an existing R codes for calculation functional depth, any of them can be depth.fd1 in ddalpha  or depth.BD, almost all of them j=2
- Check [Hausdorff distance](http://cgm.cs.mcgill.ca/~athens/cs507/Projects/2002/StephanePelletier/) on the trajectories. 
  - check if there is any difference between Hausdorff dist and point wise l2 norm.  
- maybe comment on the general problem of defining centrality in >1 dimension, e.g. @rousseeuw_bagplot_1999 ("halfspace depth"; also mentions convex hull peeling)
- show some examples of the things we've tried so far, applied to Juul's samples
- implement Juul's definitions? (These are already implemented by them in Python, could either re-implement them or make the Python stuff work in a python chunk within the rmarkdown, or in a separate script.)


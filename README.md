﻿# Development of an Optimized Algorithm for Split Delivery Vehicle Routing Problem with Time Windows

## Solution Progress Track
[ ] Chen, P., Golden, B., Wang, X., &amp; Wasil, E. (2017). A novel approach to solve the split delivery vehicle routing problem. International Transactions in Operational Research, 24(1-2), 27-41.
	
	[PDF](https://onlinelibrary.wiley.com/doi/pdf/10.1111/itor.12250)

	[VRPH library](https://projects.coin-or.org/VRPH)

###Steps
 + [x] Gather open source libarary VRPH (Groer, 2011)
 + [ ] Gather dataset used in paper

  +"The 82 instances are divided into four sets."
   +[ ] Set 1 has 11 instances from TSPLIB by Belenguer et al. (2000).
    +[ ] "... a set of 11 instances from the TSPLIB (Reinelt 1991) ... These instances are publically available via http:www.uv.es/∼belengue/SDVRP/sdvrplib.html."
     + https://www.uv.es/~belengue/SDVRP/-> Forbidden access 403 error: "...Due to changes in the security policy of the UV, on March 25, 2014 ..."**
   +[ ] Set 2 has 14 instances randomly generated using the coordinates of eil51, eil76, and eil101 from TSPLIB by Belenguer et al. (2000)
   +[ ] Set 3 has 36 instances generated by Archetti et al. (2008).
   +[ ] Set 4 has 21 instances from Chen et al. (2007).
		
 + [ ] Implement *a priori* split strategy 
 + [ ] Setup initial testing (dataset + makefile)
 + [ ] Optimization to achieve paper results
 + [ ] Optimization for better result
	
[x] Silva, M. M., Subramanian, A., &amp; Ochi, L. S. (2015). An iterated local search heuristic for the split delivery vehicle routing problem. Computers &amp; Operations Research, 53, 234-249.
	a multi-start Iterated Local Search (ILS) based heuristic that includes a novel perturbation mechanism. 
	
######Issues with makefile

[x] Berbotto, L., García, S., &amp; Nogales, F. J. (2014). A randomized granular tabu search heuristic for the split delivery vehicle routing problem. Annals of Operations Research, 222(1), 153-173.

######Issues with datasets
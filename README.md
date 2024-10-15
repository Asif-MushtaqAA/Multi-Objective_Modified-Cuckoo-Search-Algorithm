# Multi-Objective_Modified-Cuckoo-Search-Algorithm
Multi-Objective variant of Modified Cuckoo Search Algorithm

The Multi-Objective Modified Cuckoo Search Algorithm (MOMCS) is a variant of Modified Cuckoo Search Algorithm developed by Walton et al[1].   
Non-dominated sorting and crowding distance are utilised to maintain diversity among the solutions.  

In MOMCS, the parameters are similar to MCS, but with different tuning:  
	Fraction of nests to be abandoned: 0.2  
	Fraction of top nests: 0.8  

Additionally, abandoned nests in MOMCS use a larger Lévy step size A⁄∛G, enhancing exploration capabilities.   

The Algorithm is described in "MOMCS Algorithm.jpeg".	

A simple Jupyter Notebook is implementing standard benchmark functions from the Zitzler-Deb-Thiele (ZDT) family is provided here.  

References
1. Walton S, Hassan O, Morgan K, Brown MR. Modified cuckoo search: A new gradient free optimisation algorithm. Chaos Solitons Fractals [Internet]. 2011 Sep [cited 2024 Jul 20] ;44(9):710–8. Available from: http://dx.doi.org/10.1016/j.chaos.2011.06.004
